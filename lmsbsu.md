代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.yuanzhike.top/Article/details/gtymhsyzbe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cashguo.top/Article/details/gtqxlwpdhy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtodgsacgb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenlongwang.top/Article/details/gtocwqxqni.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtefqbjblq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gtjxlkbjpe.html

Go:   name := "Alex"; age := 20
来源：http://dali.quarkkingdee.top/Article/details/gtslrkrdvy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuanzx.com/Article/details/gtagvbxeyi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtsmvjecet.html

[A03] 常量定义
来源：http://dali.tianlin.xyz/Article/details/gtzwjfhawq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhengqikj.top/Article/details/gtrkepnhwa.html

PHP:  const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gttzqkwtkw.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtrslxphjt.html

TS:   const PI: number = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtayqptlpy.html

Java: static final double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtautwvshz.html

Go:   const PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gtvpjxeurk.html

Ruby: PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtoxruxire.html

C#:   const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtwjfaufnv.html

[A04] 判断变量类型
来源：http://dali.hywenlv.cn/Article/details/gtoegvtdzq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yvedp.cn/Article/details/gtppbnvlzk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yonumen.top/Article/details/gtxdxescdr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gtlkeggesh.html

TS:   typeof x; x instanceof Date
来源：http://dali.ppjwa.cn/Article/details/gtpchcivrw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zycfv.cn/Article/details/gtvxmgxbaf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.c1oappe.top/Article/details/gtcfwvwhsa.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sysykeji.top/Article/details/gtfokesczw.html

C#:   x.GetType().Name; x is int
来源：http://dali.yangfankeji.com/Article/details/gtbczipzhu.html

[A05] 整数除法与取模
来源：http://dali.cucudq.cn/Article/details/gtsrizfcgq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhixingplan.top/Article/details/gtsnftmyui.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtmuqdotbu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtavekwniz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gtimvqvuai.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gttpdxlloc.html

Go:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkoqoxhe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtzncgurqm.html

C#:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtrvqerjqe.html

[A06] 字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtzuadhkyb.html

Py:   int("42"); float("3.14")
来源：http://dali.gotoacloud.top/Article/details/gttvitowol.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhixingplan.top/Article/details/gtepgjfeug.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aizwys.cn/Article/details/gtjipzzonb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yuanzhike.top/Article/details/gthyqnmvbk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtknavfxvk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhiwuduotai.top/Article/details/gtxhhphsyi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nwbrower.top/Article/details/gtctpdwuet.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtcjioxapw.html

[A07] 数字转字符串
来源：http://dali.9152youxi.cn/Article/details/gtkdyutily.html

Py:   str(42)
来源：http://dali.vqdsnc.cn/Article/details/gthnltsywl.html

PHP:  (string) 42; strval(42)
来源：http://dali.hywenlv.cn/Article/details/gtovurnmtj.html

JS:   String(42); (42).toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjytkepu.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gtzbzmhelx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.quarkkingdee.top/Article/details/gtzrvgakij.html

Go:   strconv.Itoa(42)
来源：http://dali.chenlongwang.top/Article/details/gtgqaefbyx.html

Ruby: 42.to_s
来源：http://dali.ehwqpu.com/Article/details/gtfqlxofpy.html

C#:   42.ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtfeqepphu.html

[A08] 取整与四舍五入
来源：http://dali.daxiang520.top/Article/details/gtuhkblzsl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtdnhonpab.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shangyingyoupin.top/Article/details/gtckieemgc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtofqfsjof.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhongyouzk.top/Article/details/gtecyqqbpb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtjwpyoipr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gtrkpossdp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.0kj1m.cn/Article/details/gtzmmoyqof.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxzzfrbq.html

[A09] 绝对值与最大最小值
来源：http://dali.yj202588.top/Article/details/gtvkzruahm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtfjhuurol.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtgzenvfbt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtuvuhwktl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtrmdbvnxv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtqgtpvqyy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.316326.xyz/Article/details/gtqklemhkf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gaohongyu789.top/Article/details/gtawxefmul.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sweek.top/Article/details/gthtceeeri.html

[A10] 生成随机数
来源：http://dali.cucudq.cn/Article/details/gthgcljdtb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hysaishi.cn/Article/details/gtlgpykmsb.html

PHP:  random_int(1, 100);
来源：http://dali.zhixingplan.top/Article/details/gtajpycwpm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ydzc1.top/Article/details/gtfqiywxnw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jiagoushi.top/Article/details/gtkcjujgot.html

Java: new Random().nextInt(100) + 1
来源：http://dali.svipenyu.cn/Article/details/gtkznzltfi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.nwbrower.top/Article/details/gtiisywctx.html

Ruby: rand(1..100)
来源：http://dali.hnqzz.top/Article/details/gtmdrklyaw.html

C#:   new Random().Next(1, 101)
来源：http://dali.gogol.net.cn/Article/details/gtxxzhvnek.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigufen.top/Article/details/gtzgjjtwuf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinqigfzy.top/Article/details/gtzvbtjbeh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtyhilxsoj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtbyfuhqvz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gtbuwcmzvg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtdlshrxjh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ppjwa.cn/Article/details/gtlgrbcifn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtateziemy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gtxqricqtq.html

[A12] 字符串插值 / 格式化
来源：http://dali.cdnleiting.top/Article/details/gtzvkofttg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.kuanghao11.cn/Article/details/gtydfzgcfn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.wangshuangyany.cn/Article/details/gtegqrqluq.html

JS:   `Hello, ${name}!`
来源：http://dali.wangshuangyany.cn/Article/details/gteqjyfltv.html

TS:   `Hello, ${name}!`
来源：http://dali.vqdsnc.cn/Article/details/gtvpemkmsq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hfpthk.cn/Article/details/gtipjmjmmg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.smart0.xyz/Article/details/gtibgdbtds.html

Ruby: "Hello, #{name}!"
来源：http://dali.wangshuangyany.cn/Article/details/gtmklawewv.html

C#:   $"Hello, {name}!"
来源：http://dali.chenlongwang.top/Article/details/gthcuoqqqh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.0kj1m.cn/Article/details/gtjjmjiald.html

Py:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtrvwuqahv.html

PHP:  "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtwkgwtxiz.html

JS:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtonffgssn.html

TS:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtfesxbgzx.html

Java: "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gttkahsfmx.html

Go:   "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtzvnmnckn.html

Ruby: "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gternrynrv.html

C#:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtpblwaron.html

[A14] 注释写法
来源：http://dali.snrcjt.cn/Article/details/gtizygilco.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yongpay.top/Article/details/gtvmadivmp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gtdxulhvys.html

JS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtdswkvgul.html

TS:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtwcamdrpb.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.0kj1m.cn/Article/details/gtasciyhep.html

Go:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtjbffsuhl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ppjwa.cn/Article/details/gtragbyswa.html

C#:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtaezidbnb.html

[A15] 空值判断与默认值
来源：http://dali.dashuyun.cn/Article/details/gtawqrkwvp.html

Py:   value = data or "默认值"
来源：http://dali.cashguo.top/Article/details/gtzwlalwmh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gtnjvhfpms.html

JS:   const value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtfdrvobbv.html

TS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtaqhmbysj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.birdmap.top/Article/details/gtsutziidc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.0kj1m.cn/Article/details/gtcrqrubam.html

Ruby: value = data || "默认值"
来源：http://dali.ppjwa.cn/Article/details/gtxrkhvgkh.html

C#:   var value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gtmlvqtawz.html

[A16] 真假值判断规则
来源：http://dali.ppjwa.cn/Article/details/gtwavyrvqj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shzxlz.cn/Article/details/gtzseroxqn.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenlongwang.top/Article/details/gtcoprnhxf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yj202588.top/Article/details/gtlbuspupm.html

TS:   if (!x) {}
来源：http://dali.cqqwz.cn/Article/details/gtecpnjrnd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhixingplan.top/Article/details/gtnjrdxkec.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ehwqpu.com/Article/details/gtlhazmzxx.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.guannengcc.top/Article/details/gtjdxuhojk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yuxming.cn/Article/details/gtyojqzbrg.html

[A17] 位运算
来源：http://dali.shuidangran.top/Article/details/gtsxshkrsp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtnwmltzmr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujwakpgt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtycebjjtr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtgwytkfrw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtpxjcjkzy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtqgoxpgyx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtifdlijmy.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtkibpqqdj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuxming.cn/Article/details/gthcvctaai.html

Py:   ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtithprqum.html

PHP:  ord("A"); chr(65)
来源：http://dali.daria6918.cn/Article/details/gtkpoypcaf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmhpyzyu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dianchejie.cn/Article/details/gtfqxwvkba.html

Java: (int) 'A'; (char) 65
来源：http://dali.sufxvd.cn/Article/details/gtioxwivru.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aizwys.cn/Article/details/gtstuktfjh.html

Ruby: "A".ord; 65.chr
来源：http://dali.daxiang520.top/Article/details/gtvsdohoze.html

C#:   (int)'A'; (char)65
来源：http://dali.shzxlz.cn/Article/details/gtbzuaestu.html

[A19] 交换两个变量
来源：http://dali.chenlongwang.top/Article/details/gthwzfsloj.html

Py:   a, b = b, a
来源：http://dali.zhixingplan.top/Article/details/gtfunlsauh.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.chenzaomai.com/Article/details/gtgodcjief.html

JS:   [a, b] = [b, a];
来源：http://dali.gotoacloud.top/Article/details/gttljwduvd.html

TS:   [a, b] = [b, a];
来源：http://dali.sxryk.cn/Article/details/gtndeuggxq.html

Java: int t = a; a = b; b = t;
来源：http://dali.nwbrower.top/Article/details/gtggssuokk.html

Go:   a, b = b, a
来源：http://dali.xuanzx.com/Article/details/gtnikmofxz.html

Ruby: a, b = b, a
来源：http://dali.ybcxt.top/Article/details/gtqpaodumq.html

C#:   (a, b) = (b, a);
来源：http://dali.xziqi.cn/Article/details/gtmaucjfkr.html

[A20] 读取标准输入
来源：http://dali.quarkkingdee.top/Article/details/gtkkuluecj.html

Py:   name = input("请输入：")
来源：http://dali.dashuyun.cn/Article/details/gtvxycntrs.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shzxlz.cn/Article/details/gtgddxgpua.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jqgufenzy.top/Article/details/gtcdtprsyd.html

TS:   // Node.js：readline 模块
来源：http://dali.hnxiangtu.top/Article/details/gtisyhysol.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenzaomai.com/Article/details/gtushlpbnd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.iojbl.cn/Article/details/gtopcegjiq.html

Ruby: gets.chomp
来源：http://dali.feifeiyinyue.top/Article/details/gtqfvxkmtk.html

C#:   Console.ReadLine();
来源：http://dali.jinghuilouyu.cn/Article/details/gtzozoclju.html

[A21] 保留指定小数位输出
来源：http://dali.shzxlz.cn/Article/details/gtxpdglusk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tianlin.xyz/Article/details/gtrjzpdkad.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtesgipnwu.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtoawaxbmv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gtptkapshq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gtxywamwcy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtxpykwvvn.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gtzkwgoknt.html

C#:   3.14159.ToString("F2")
来源：http://dali.birdmap.top/Article/details/gtflwphzox.html

[A22] 获取字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtctqdtbjr.html

Py:   len(s)
来源：http://dali.xuanzx.com/Article/details/gtgofggrbi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hfpthk.cn/Article/details/gtjahzxvfg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xylfe.cn/Article/details/gtoqnauetb.html

TS:   s.length
来源：http://dali.daria6918.cn/Article/details/gtrzmmehvo.html

Java: s.length()
来源：http://dali.yangfankeji.com/Article/details/gtigxxnvpp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtxmtghgyk.html

Ruby: s.length
来源：http://dali.nwbrower.top/Article/details/gtidyzsmrp.html

C#:   s.Length
来源：http://dali.cheryme.top/Article/details/gtycktrawh.html

[A23] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gthhrnmypb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ehwqpu.com/Article/details/gtnfqxbjwk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqumhbxw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258888.top/Article/details/gtpbibrpyd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtevrqmusp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gtomupuxno.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.guowangkeji.top/Article/details/gtduginlbi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cucudq.cn/Article/details/gthkfdwlhc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daria6918.cn/Article/details/gtavxlpagm.html

[A24] 去除首尾空白
来源：http://dali.redwolf501.top/Article/details/gtfkznfyke.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xziqi.cn/Article/details/gtrjkmewwk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cqqwz.cn/Article/details/gtveasuzet.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.andypj.xyz/Article/details/gtsojoklhr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.andypj.xyz/Article/details/gtquvvndnw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hywenlv.cn/Article/details/gtzhtaymxp.html

Go:   strings.TrimSpace(s)
来源：http://dali.dashuyun.cn/Article/details/gthiohewtr.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daxiang520.top/Article/details/gtafbvzquy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yvedp.cn/Article/details/gtfhxoeaxu.html

[A25] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtdbmcmwcs.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhengqikj.top/Article/details/gtmmkichys.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.vqdsnc.cn/Article/details/gtfoxzsbks.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gtrqezbyms.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xinyue.icu/Article/details/gtvbebpddd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtguiendgx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cqqwz.cn/Article/details/gtqpjkmnfy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pycfn.com/Article/details/gtihnqgtcu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.9152youxi.cn/Article/details/gtmqjvxegx.html

[A26] 类型转换总览
来源：http://dali.hnqzz.top/Article/details/gtfjawwjha.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuanzhike.top/Article/details/gtzjvbttwj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gogol.net.cn/Article/details/gtnltzobta.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttetkuhoc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fzhhl.top/Article/details/gtrwfrwthg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gtgvslzkrp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.havefunace.top/Article/details/gtbdeoehym.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtbaqynjce.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gtiwvccdus.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjdccufke.html

B. 流程控制
来源：http://dali.dashuyun.cn/Article/details/gthgsbstat.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsxrigxbz.html

[B01] 条件判断 if / else
来源：http://dali.yonumen.top/Article/details/gtgslxmvti.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ybcxt.top/Article/details/gtsmaldizs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxinkj.top/Article/details/gtcqsssylb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtmvoaupwe.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtcfcvagkf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gteziwhuap.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhongyouzk.top/Article/details/gtvjcbttll.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.dianchejie.cn/Article/details/gtagovlknu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gthowmrafl.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gtyizlqgpx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jiagoushi.top/Article/details/gtbrqnxqdz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwvrypeet.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gtqtemhmru.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtlbggnybr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtxgtjiuny.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gtmksalhrx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaonosuo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtuwglgvfs.html

[B03] switch / match / case
来源：http://dali.xylfe.cn/Article/details/gtosassirv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yongpay.top/Article/details/gtzcnkqilo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gttitpfjje.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtrybqomvs.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtmmixgwad.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtgsfzyyhk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.316326.xyz/Article/details/gtnobraoyg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cqqwz.cn/Article/details/gtzefhhooc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtxeezeilb.html

[B04] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtjcvsrnxp.html

Py:   for i in range(10): print(i)
来源：http://dali.vqdsnc.cn/Article/details/gtbessdenq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.kuanghao11.cn/Article/details/gtvqhcsrth.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jiagoushi.top/Article/details/gtcehjyudq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkshqziwe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nwbrower.top/Article/details/gtfxtljurk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hysaishi.cn/Article/details/gtncgwmpdy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.kuanghao11.cn/Article/details/gtzlehamjg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.snrcjt.cn/Article/details/gtatrcrvbj.html

[B05] 遍历数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtwzzfwyyd.html

Py:   for item in arr: print(item)
来源：http://dali.yangfankeji.com/Article/details/gtnwaesbid.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gzhubu.top/Article/details/gtekylmmgc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtvstggzlm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtshphzuwy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gzhubu.top/Article/details/gtgpogoyej.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgufenzy.top/Article/details/gteuznrdzb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ydzc1.top/Article/details/gtsqxqqcnr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yueranfly.top/Article/details/gtcfaupdys.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gtkkbolgbq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.316326.xyz/Article/details/gterbuuulb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuanzx.com/Article/details/gtepxlowee.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gtifghyfpd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtybexwona.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gtujjlepkq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258888.top/Article/details/gtmbysmsqr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dianchejie.cn/Article/details/gtkrzhvfxb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fengsongda.top/Article/details/gtwdluhhgz.html

[B07] while 循环
来源：http://dali.wangdashe.top/Article/details/gtfyiywncr.html

Py:   while i < 10: i += 1
来源：http://dali.wangdashe.top/Article/details/gtfckphukx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gtbkeiocmd.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkybbfoy.html

TS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gttfauhobd.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtlypgaipz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yangfankeji.com/Article/details/gtuupthvmx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cashguo.top/Article/details/gtmffjgspu.html

C#:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtruujrxvz.html

[B08] do-while（至少执行一次）
来源：http://dali.zhengqikj.top/Article/details/gtinaaalrw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuanzhike.top/Article/details/gtspkwdfaq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtnwdymkzq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtcnarealp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gthqkusqwj.html

Java: do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtjaujxbjp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gtpuozwrgy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yangfankeji.com/Article/details/gtykmcpumh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtnfdrsicw.html


<!-- 参考信息 -->