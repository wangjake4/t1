代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.smart0.xyz/Article/details/gt2iaucpzov.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wucvtuou.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gt2jlxzawvx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gt2xdydqurs.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2hantsyya.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gt2opbjqvji.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2fzcejhmh.html

[A01] Hello World
来源：http://dali.yongpay.top/Article/details/gt2rbdtvmld.html

Py:   print("Hello, World!")
来源：http://dali.birdmap.top/Article/details/gt2mdiorfvw.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgufenzy.top/Article/details/gt2mofnqicu.html

JS:   console.log("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gt2dvedlfyg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijgewqyk.html

Java: System.out.println("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjkpawzq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gt2bvwvjqdb.html

Ruby: puts "Hello, World!"
来源：http://dali.cdnleiting.top/Article/details/gt2ouxqmowc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gt2byqgkphn.html

[A02] 变量声明与赋值
来源：http://dali.sysykeji.top/Article/details/gt2revjckja.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sxryk.cn/Article/details/gt2gctkwazg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2naucqjkl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljdlisma.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tanke756.top/Article/details/gt2pglebxim.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2uscmgxid.html

Go:   name := "Alex"; age := 20
来源：http://dali.daxiang520.top/Article/details/gt2doncqswk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj202588.top/Article/details/gt2dvhgybdg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jswwdbet.html

[A03] 常量定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhcfswvb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sweek.top/Article/details/gt2loxdxuah.html

PHP:  const PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2teutinom.html

JS:   const PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2jnawcdlc.html

TS:   const PI: number = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2zwhfzdxy.html

Java: static final double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2xxvscjkf.html

Go:   const PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gt2slbtadiw.html

Ruby: PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gt2pdrnbggx.html

C#:   const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2jjtaalkp.html

[A04] 判断变量类型
来源：http://dali.yueranfly.top/Article/details/gt2cdjcyswb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shzxlz.cn/Article/details/gt2hjcdgbrt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhouokwy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gt2ccgefspj.html

TS:   typeof x; x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gt2nbgxrdjm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhiwuduotai.top/Article/details/gt2izhyzmxn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvwmgheh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hnqzz.top/Article/details/gt2bdzennrp.html

C#:   x.GetType().Name; x is int
来源：http://dali.yvedp.cn/Article/details/gt2yhwgqrio.html

[A05] 整数除法与取模
来源：http://dali.jqgfzy.top/Article/details/gt2eltautdf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nekljsya.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2vlhmrdxy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2jewnynge.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nntvblqy.html

Java: 7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2ekudvfww.html

Go:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmvvppdz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2izfkfjig.html

C#:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2muaqzgup.html

[A06] 字符串转数字
来源：http://dali.pycfn.com/Article/details/gt2hwsskcml.html

Py:   int("42"); float("3.14")
来源：http://dali.hywenlv.cn/Article/details/gt2cuifnmru.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenlongwang.top/Article/details/gt2nfptimpw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shzxlz.cn/Article/details/gt2orpeckzc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cheryme.top/Article/details/gt2ywqwgpsm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sufxvd.cn/Article/details/gt2lyjnjmps.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shzxlz.cn/Article/details/gt2ordxqqch.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sweek.top/Article/details/gt2ckicbwfk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhtsdcgg.html

[A07] 数字转字符串
来源：http://dali.andypj.xyz/Article/details/gt2icpddywo.html

Py:   str(42)
来源：http://dali.hywenlv.cn/Article/details/gt2xwdxmakg.html

PHP:  (string) 42; strval(42)
来源：http://dali.pycfn.com/Article/details/gt2nnygjqby.html

JS:   String(42); (42).toString()
来源：http://dali.daxiang520.top/Article/details/gt2cweaxgpo.html

TS:   String(42)
来源：http://dali.kuanghao11.cn/Article/details/gt2hkmozoqk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yongpay.top/Article/details/gt2xonnejko.html

Go:   strconv.Itoa(42)
来源：http://dali.9152youxi.cn/Article/details/gt2bijomklu.html

Ruby: 42.to_s
来源：http://dali.sxryk.cn/Article/details/gt2qbnzcjbm.html

C#:   42.ToString()
来源：http://dali.zhoulong.xyz/Article/details/gt2xjfxmbpz.html

[A08] 取整与四舍五入
来源：http://dali.snrcjt.cn/Article/details/gt2hixjklhj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2pbtflwel.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jlsjyb.cn/Article/details/gt2rrrktmwb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gt2zqcndrdb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.svipenyu.cn/Article/details/gt2cjoksoop.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gt2pdkufvab.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gt2kdywogli.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigufen.top/Article/details/gt2kkgvzwqe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gt2ivmclptp.html

[A09] 绝对值与最大最小值
来源：http://dali.sufxvd.cn/Article/details/gt2hyhecbnp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2hpkzqifr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2iwsnkcfb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwzffzac.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2uvuppepy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2ydcgzadw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yueranfly.top/Article/details/gt2pjhemabc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj20258888.top/Article/details/gt2ypsojdbk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdhxnguc.html

[A10] 生成随机数
来源：http://dali.fzhhl.top/Article/details/gt2tgegujpk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hysaishi.cn/Article/details/gt2jvvplaie.html

PHP:  random_int(1, 100);
来源：http://dali.gzhubu.top/Article/details/gt2zlxkooat.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cqqwz.cn/Article/details/gt2lpkuocuz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gzhubu.top/Article/details/gt2sjcuxtfh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sufxvd.cn/Article/details/gt2pkloggoi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zdqjudy.top/Article/details/gt2yfgvdhpi.html

Ruby: rand(1..100)
来源：http://dali.gogol.net.cn/Article/details/gt2ypryneak.html

C#:   new Random().Next(1, 101)
来源：http://dali.cheryme.top/Article/details/gt2chxyvfrr.html

[A11] 条件表达式（三元）
来源：http://dali.jqgfzy.top/Article/details/gt2xwsytpow.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcloiqgx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gt2pmhlwaan.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gt2xmipfygj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gt2ukvdvzfh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gt2qbnyjqsa.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbrhjfzx.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gt2gwhxpoqz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gt2wrifhvjg.html

[A12] 字符串插值 / 格式化
来源：http://dali.0kj1m.cn/Article/details/gt2iadcyqao.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gzhubu.top/Article/details/gt2utbakmqa.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.tian-w.cn/Article/details/gt2kjkzpfml.html

JS:   `Hello, ${name}!`
来源：http://dali.9152youxi.cn/Article/details/gt2pdzzpfhd.html

TS:   `Hello, ${name}!`
来源：http://dali.hfpthk.cn/Article/details/gt2sffbxpto.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.svipenyu.cn/Article/details/gt2picxiquu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hammf.cn/Article/details/gt2ocztqnzj.html

Ruby: "Hello, #{name}!"
来源：http://dali.cdnleiting.top/Article/details/gt2fbkwzupn.html

C#:   $"Hello, {name}!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddecgoeq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.pycfn.com/Article/details/gt2xxbbvguv.html

Py:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2vleqgzbe.html

PHP:  "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2jzlazwyl.html

JS:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gt2wcyfffau.html

TS:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2ycromnvu.html

Java: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2zfcljfgu.html

Go:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gt2dvjlgxxu.html

Ruby: "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gt2pjxgskah.html

C#:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gt2gqyohmji.html

[A14] 注释写法
来源：http://dali.hnqzz.top/Article/details/gt2fqpymdzv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.bjfxy.top/Article/details/gt2uppvmfmx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfrirrji.html

JS:   // 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gt2xmymhxvz.html

TS:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gt2qjzhndcc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nwbrower.top/Article/details/gt2qtkiyese.html

Go:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2qbcnkmwu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbudlvmr.html

C#:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gt2tyjtbgoq.html

[A15] 空值判断与默认值
来源：http://dali.gogol.net.cn/Article/details/gt2rtwzavtl.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2osmptmjr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gt2wdvjkyoh.html

JS:   const value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gt2rdkirmes.html

TS:   const value = data ?? "默认值";
来源：http://dali.xylfe.cn/Article/details/gt2grhzaovs.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.fzhhl.top/Article/details/gt2ramaezxr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.wangdashe.top/Article/details/gt2twtzzkxi.html

Ruby: value = data || "默认值"
来源：http://dali.smart0.xyz/Article/details/gt2diadmrca.html

C#:   var value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gt2ikokzbuj.html

[A16] 真假值判断规则
来源：http://dali.haohaochexian.top/Article/details/gt2ctemsnvv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfturmej.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.bjfxy.top/Article/details/gt2lmuzhhut.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cqqwz.cn/Article/details/gt2jwsmgebj.html

TS:   if (!x) {}
来源：http://dali.nwbrower.top/Article/details/gt2mffhzkux.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2iagjrgeo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gogol.net.cn/Article/details/gt2kjabqxua.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ehwqpu.com/Article/details/gt2cbcgxiet.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2djuqzzxo.html

[A17] 位运算
来源：http://dali.ehwqpu.com/Article/details/gt2howmabft.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gt2dpxdchta.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwkarebl.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2rersfgxi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gopbpozb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gt2dqgiekcn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2aboddpgo.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2cioihqjl.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gt2myciwren.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cdnleiting.top/Article/details/gt2cactfwcq.html

Py:   ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gt2tcjqisrn.html

PHP:  ord("A"); chr(65)
来源：http://dali.gaohongyu789.top/Article/details/gt2bruxledj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hysaishi.cn/Article/details/gt2vfbvhygh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.havefunace.top/Article/details/gt2kcqifqqq.html

Java: (int) 'A'; (char) 65
来源：http://dali.tianlin.xyz/Article/details/gt2djvmnrav.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ybcxt.top/Article/details/gt2npqparta.html

Ruby: "A".ord; 65.chr
来源：http://dali.meibo888.top/Article/details/gt2lntidcma.html

C#:   (int)'A'; (char)65
来源：http://dali.jyoumei.cn/Article/details/gt2zskscwcm.html

[A19] 交换两个变量
来源：http://dali.chenlongwang.top/Article/details/gt2kkccugzc.html

Py:   a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gt2gvaagssn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpxhoarj.html

JS:   [a, b] = [b, a];
来源：http://dali.nanxinkj.top/Article/details/gt2cmoichle.html

TS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbbvfihh.html

Java: int t = a; a = b; b = t;
来源：http://dali.nanxinkj.top/Article/details/gt2lpocbpzt.html

Go:   a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gt2bpesfpyx.html

Ruby: a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gt2yjnnjsix.html

C#:   (a, b) = (b, a);
来源：http://dali.yanxiufei.cn/Article/details/gt2jtcjkald.html

[A20] 读取标准输入
来源：http://dali.zhiwuduotai.top/Article/details/gt2huciusqv.html

Py:   name = input("请输入：")
来源：http://dali.birdmap.top/Article/details/gt2iuhtaoon.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.9152youxi.cn/Article/details/gt2pqszqeat.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.andypj.xyz/Article/details/gt2uagtbbrw.html

TS:   // Node.js：readline 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2nlmglsvd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jiagoushi.top/Article/details/gt2mgefulsp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj202588.top/Article/details/gt2uvjuchbo.html

Ruby: gets.chomp
来源：http://dali.yuanzhike.top/Article/details/gt2izhrmrlu.html

C#:   Console.ReadLine();
来源：http://dali.iojbl.cn/Article/details/gt2ptvqjeij.html

[A21] 保留指定小数位输出
来源：http://dali.ehwqpu.com/Article/details/gt2axbdhaku.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fengsongda.top/Article/details/gt2pmtzriae.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gt2lhrprwfr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gt2otvjqgsj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gt2uaryklys.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gt2xsouznii.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gt2ugmkelbq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gt2pxxllltm.html

C#:   3.14159.ToString("F2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajeaxuvp.html

[A22] 获取字符串长度
来源：http://dali.bjfxy.top/Article/details/gt2bmkxbnqc.html

Py:   len(s)
来源：http://dali.yonumen.top/Article/details/gt2fgxeyuhv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.redwolf501.top/Article/details/gt2ipyclovq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.guowangkeji.top/Article/details/gt2gdrmfzvk.html

TS:   s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2voctrnpn.html

Java: s.length()
来源：http://dali.zhengqikj.top/Article/details/gt2vmruihyh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.bjfxy.top/Article/details/gt2adhmouhe.html

Ruby: s.length
来源：http://dali.cqqwz.cn/Article/details/gt2vusmpgid.html

C#:   s.Length
来源：http://dali.9152youxi.cn/Article/details/gt2htfznwhd.html

[A23] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gt2thdknbdp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjufoqvd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shuidangran.top/Article/details/gt2lsgnmnul.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gt2svvwytaa.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gt2ufrssefh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gt2uxaaljfb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cqqwz.cn/Article/details/gt2spxiaoyo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gt2swxgxquo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sxryk.cn/Article/details/gt2apmpqbgy.html

[A24] 去除首尾空白
来源：http://dali.xinyue.icu/Article/details/gt2qjgccfbq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hnxiangtu.top/Article/details/gt2quutfjnv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tanke756.top/Article/details/gt2ziqlaldb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yvedp.cn/Article/details/gt2pbfzgpzc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yonumen.top/Article/details/gt2ulocoxkb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ivvv.top/Article/details/gt2fdgqbpta.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnhhwoqp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hfpthk.cn/Article/details/gt2wtcevnzg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.mhx1999.top/Article/details/gt2kabupxls.html

[A25] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2jwviwbdb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daria6918.cn/Article/details/gt2buqkclro.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuyqrhre.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gt2txpiyzcv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gt2coyscogp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jiagoushi.top/Article/details/gt2pljpdikc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2secitqot.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.snrcjt.cn/Article/details/gt2nogqpknm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gt2fxdilraq.html

[A26] 类型转换总览
来源：http://dali.svipenyu.cn/Article/details/gt2hcwbtvrd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zdqjudy.top/Article/details/gt2sbzlpqwk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.mhx1999.top/Article/details/gt2ghprqnez.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gotoacloud.top/Article/details/gt2qvamtffn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adkoaguq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gt2wakohmzm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2unogmtlv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.dianchejie.cn/Article/details/gt2hcawffyf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xuanzx.com/Article/details/gt2aobveqtq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2uimnugnc.html

B. 流程控制
来源：http://dali.sxryk.cn/Article/details/gt2onslypvn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2icxgiwmg.html

[B01] 条件判断 if / else
来源：http://dali.pengpengdd.cyou/Article/details/gt2eatkxweg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cheryme.top/Article/details/gt2slepubze.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.smart0.xyz/Article/details/gt2fzvmtvof.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gt2uvcvffov.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2vansnplw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gt2oothuwcg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sweek.top/Article/details/gt2skeojvqk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daxiang520.top/Article/details/gt2gpykucot.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gt2vevmbdtx.html

[B02] 多分支 else if / elif
来源：http://dali.ybcxt.top/Article/details/gt2ridhgwcy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.guannengcc.top/Article/details/gt2qxarmrqv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sweek.top/Article/details/gt2gpqmklev.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2mldsuhlv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gt2vgymizet.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gt2htuuxoty.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fengsongda.top/Article/details/gt2xrvsqbwj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj202588.top/Article/details/gt2dmruhefc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gt2qoezqtaw.html

[B03] switch / match / case
来源：http://dali.yonumen.top/Article/details/gt2qmwvhvaa.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ydzc1.top/Article/details/gt2hzhlgvag.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gt2kwcozggs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gt2hjdpcicl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gt2ormfabtm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gt2swfsuzuk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gt2roogsoux.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj202588.top/Article/details/gt2traaqqoj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gt2ymetlvsb.html

[B04] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gt2icirouof.html

Py:   for i in range(10): print(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2scpzwttv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aibaodan.cn/Article/details/gt2kopffblp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gt2pvxrxuec.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gt2kvzxfddo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2ryuhoone.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mveuzrqn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgsfvyg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.daxiang520.top/Article/details/gt2plirjvrc.html

[B05] 遍历数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gt2hbmehrje.html

Py:   for item in arr: print(item)
来源：http://dali.yvedp.cn/Article/details/gt2mzfdtwts.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhengqikj.top/Article/details/gt2agiyiooa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zycfv.cn/Article/details/gt2qxvzkllj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2cerkkknh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgufenzy.top/Article/details/gt2qflcyimc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jiagoushi.top/Article/details/gt2xetssebt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258888.top/Article/details/gt2cuzmidth.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhengqikj.top/Article/details/gt2iphqfzaj.html

[B06] 遍历字典 / 对象
来源：http://dali.shuidangran.top/Article/details/gt2imuvvvdr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sufxvd.cn/Article/details/gt2cfkwgfzz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdzzfqg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gt2krpefowf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsyqhqbu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenzaomai.com/Article/details/gt2qtoxuavp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangdashe.top/Article/details/gt2eqxksxcp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dianchejie.cn/Article/details/gt2fwbotfkd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gt2gtbwbzqr.html

[B07] while 循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqhrfwps.html

Py:   while i < 10: i += 1
来源：http://dali.yuxming.cn/Article/details/gt2rgryiuie.html


<!-- 参考信息 -->