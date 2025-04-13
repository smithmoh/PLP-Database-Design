<h2>📚 Bookstore Database Schema</h2>
 
 This repository has a base task of designing a database schema; this task was assigned to : <ul style="list-style:none;"> <li>Grace Ngari</li> <li>Moses Simiyu</li> <li>Jesse Ager</li> </ul>

<p>The schema is about designing and implementing a relational database system for managing the operations of a bookstore. It includes tables for books, authors, customers, orders, shipping, and more, supporting data integrity, relationships, and access control.</p>

<h3>🗂️ Core Tables</h3>
<ul>
  <li><strong>book</strong>: Stores information about books available in the store.</li>
  <li><strong>author</strong>: Contains author details.</li>
  <li><strong>book_author</strong>: Manages the many-to-many relationship between books and authors.</li>
  <li><strong>book_language</strong>: Lists supported languages for books.</li>
  <li><strong>publisher</strong>: Holds data on book publishers.</li>
</ul>

<h3>👥 Customer & Address Management</h3>
<ul>
  <li><strong>customer</strong>: Stores customer details.</li>
  <li><strong>address</strong>: Holds all physical addresses.</li>
  <li><strong>country</strong>: Reference table for countries.</li>
  <li><strong>address_status</strong>: Status of addresses (e.g., current, old).</li>
  <li><strong>customer_address</strong>: Links customers to their multiple addresses.</li>
</ul>

<h3>🛒 Orders & Fulfillment</h3>
<ul>
  <li><strong>cust_order</strong>: Records customer orders.</li>
  <li><strong>order_line</strong>: Lists books in each order with quantities and price.</li>
  <li><strong>shipping_method</strong>: Available shipping options.</li>
  <li><strong>order_status</strong>: Status values like pending, delivered, etc.</li>
  <li><strong>order_history</strong>: Tracks changes in order status over time.</li>
</ul>

<h3>🔐 Security & User Management</h3>
<ul>
  <li><strong>book_admin</strong>: A database user with full privileges.</li>
  <li><strong>book_user</strong>: A restricted user with read and limited write access.</li>
  <li>Privileges are assigned to maintain proper role-based access control.</li>
</ul>

<h3>✅ Features</h3>
<ul>
  <li>Relational structure with foreign key constraints</li>
  <li>Support for many-to-many relationships</li>
  <li>Secure and role-based user access</li>
  <li>Normalized design for efficient storage and querying</li>
</ul>
