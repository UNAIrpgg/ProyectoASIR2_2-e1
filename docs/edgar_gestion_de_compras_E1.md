# 📘 Documentación Odoo - Tarea 6

## 🛒 Paso 4: Gestión de una Compra - Pedidos a Proveedores

Odoo permite gestionar compras y órdenes de compra con proveedores para mantener el inventario abastecido.

![SRI](/ProyectoASIR-e1/docs/img-odoo/compras.PNG)

### 📜 **4.1 Creación de un Pedido de Compra**
#### 🔹 **Pasos para realizar una compra en Odoo:**
![SRI](/ProyectoASIR-e1/docs/img-odoo/pedidos_compra.PNG)
1. Accede al módulo **Compras**.
2. Selecciona **Pedidos de compra > Crear**.
![SRI](/ProyectoASIR-e1/docs/img-odoo/pedido_compra1.PNG)
3. Completa los siguientes campos:
   - **Proveedor**: Selecciona o crea un nuevo proveedor.
   ![SRI](/ProyectoASIR-e1/docs/img-odoo/pedido_compra2.PNG)
   - **Fecha del pedido**.
   ![SRI](/ProyectoASIR-e1/docs/img-odoo/pedido_compra3.PNG)
   - **Productos**: Añade los productos a comprar.
   ![SRI](/ProyectoASIR-e1/docs/img-odoo/pedido_compra4.PNG)
   - **Cantidad y precio unitario**.
   - **Moneda** (si aplica).
4. Guarda el pedido.
![SRI](/ProyectoASIR-e1/docs/img-odoo/pedido_compra_general.PNG)
---

### 📦 **4.2 Validación y Recepción del Pedido**
1. En el pedido de compra, haz clic en **Confirmar pedido**.
![SRI](/ProyectoASIR-e1/docs/img-odoo/confirmar_pedido.PNG)
2. Odoo generará automáticamente un albarán de recepción en el módulo de **Inventario**.
![SRI](/ProyectoASIR-e1/docs/img-odoo/inventario.PNG)
3. Para registrar la llegada de los productos:
   - Accede al módulo **Inventario**.
   - Ve a **Recepciones > Pedidos pendientes**.
   ![SRI](/ProyectoASIR-e1/docs/img-odoo/recepciones_pedidos_pendientes.PNG)
   - Confirma la recepción de productos.
   - Haz clic en **Validar** para actualizar el stock.
   ![SRI](/ProyectoASIR-e1/docs/img-odoo/validar.PNG)
   - Validación finalizada
   ![SRI](/ProyectoASIR-e1/docs/img-odoo/validacion_hecha.PNG)

---

### 💰 **4.3 Facturación del Pedido**
Una vez recibidos los productos, se puede generar la factura para el proveedor.

1. Accede al módulo **Compras**.
2. Abre el pedido de compra confirmado.
3. Haz clic en **Crear factura**.
![SRI](/ProyectoASIR-e1/docs/img-odoo/crear_factura.PNG)
4. Revisa los detalles y selecciona el estado:
   - **Borrador**: Pendiente de validación.
   ![SRI](/ProyectoASIR-e1/docs/img-odoo/factura_borrador.PNG)
   - **Publicada**: Factura lista para pago.
   ![SRI](/ProyectoASIR-e1/docs/img-odoo/factura_publicada.PNG)
5. Guarda y valida la factura.
![SRI](/ProyectoASIR-e1/docs/img-odoo/facturacion_compra.PNG)

![SRI](/ProyectoASIR-e1/docs/img-odoo/pagar.PNG)
---

## 📌 Conclusión

Con estos pasos, hemos gestionado la compra a proveedores en Odoo. Esto permite una correcta administración del inventario y optimiza el flujo de stock. 🚀

---

#### Realizado por Edgar Díaz Martínez
