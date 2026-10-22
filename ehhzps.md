代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jiagoushi.top/Article/details/gt2gjtofkcd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gotoacloud.top/Article/details/gt2wjkfmxcd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gt2gyjhjvek.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2mphvmfyj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2hupgjsab.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffierxye.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rbnlrggx.html

[A01] Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnnaweym.html

Py:   print("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvwezpdt.html

PHP:  echo "Hello, World!";
来源：http://dali.ivvv.top/Article/details/gt2xgrorinc.html

JS:   console.log("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gt2eztnggoh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xziqi.cn/Article/details/gt2oxsiteyp.html

Java: System.out.println("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gt2zvlhiist.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenlongwang.top/Article/details/gt2crshvdns.html

Ruby: puts "Hello, World!"
来源：http://dali.sweek.top/Article/details/gt2whzdgxmj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gt2pwuzcsyc.html

[A02] 变量声明与赋值
来源：http://dali.xylfe.cn/Article/details/gt2yvwulero.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icyckpbp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gt2vbtgiuxo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2xegcqger.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zploutxb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gt2gidmcckw.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gt2mabsugqv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xylfe.cn/Article/details/gt2mdtacmkb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2eidaxdgn.html

[A03] 常量定义
来源：http://dali.fzhhl.top/Article/details/gt2ncefcuqa.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjhfsbbz.html

PHP:  const PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2ziumavrj.html

JS:   const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2aipjklct.html

TS:   const PI: number = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2ckttskwg.html

Java: static final double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2kymzqufy.html

Go:   const PI = 3.14159
来源：http://dali.bjfxy.top/Article/details/gt2svskmvrh.html

Ruby: PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gt2qhauigxp.html

C#:   const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2cgypbqua.html

[A04] 判断变量类型
来源：http://dali.vqdsnc.cn/Article/details/gt2mmyohfxq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.aibaodan.cn/Article/details/gt2hiokfxnm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenlongwang.top/Article/details/gt2uaxdpwwa.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsuzlfuw.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gt2qddpkwja.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.mhx1999.top/Article/details/gt2bdxyftay.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gogol.net.cn/Article/details/gt2pffcwxhb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj202588.top/Article/details/gt2itgzrqem.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhongyouzk.top/Article/details/gt2tcuszjkm.html

[A05] 整数除法与取模
来源：http://dali.guannengcc.top/Article/details/gt2crdeludl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zycfv.cn/Article/details/gt2ehacdqmq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2hkeduosl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjpfahbr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2tmsjflqb.html

Java: 7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gt2kavghpgt.html

Go:   7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gt2qzhhqhfd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2qpwugfgu.html

C#:   7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2brcijipe.html

[A06] 字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gt2ngfmsrhj.html

Py:   int("42"); float("3.14")
来源：http://dali.hysaishi.cn/Article/details/gt2tmpltlsr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bedoegev.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gt2wqiojaoz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gt2ytqhyjbn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gt2cvhcmool.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sufxvd.cn/Article/details/gt2iourbxyd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daxiang520.top/Article/details/gt2pmrrxgsv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wazurkze.html

[A07] 数字转字符串
来源：http://dali.yj20258.top/Article/details/gt2buawejrl.html

Py:   str(42)
来源：http://dali.hfpthk.cn/Article/details/gt2asxfatqq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zycfv.cn/Article/details/gt2vlmnpcrt.html

JS:   String(42); (42).toString()
来源：http://dali.zdqjudy.top/Article/details/gt2bfzkzxbs.html

TS:   String(42)
来源：http://dali.jianghu66.top/Article/details/gt2anhkhroy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cdnleiting.top/Article/details/gt2cednrmop.html

Go:   strconv.Itoa(42)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jguevjfw.html

Ruby: 42.to_s
来源：http://dali.shangyingyoupin.top/Article/details/gt2wodehgar.html

C#:   42.ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2zwmpgkth.html

[A08] 取整与四舍五入
来源：http://dali.zhengqikj.top/Article/details/gt2fatotcmv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gt2cuhmiega.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jyoumei.cn/Article/details/gt2odzlatzo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj202588.top/Article/details/gt2lcbcubly.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guannengcc.top/Article/details/gt2wqgvvphf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gt2xovgjnmz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gt2cmpftbrl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.316326.xyz/Article/details/gt2eecbpotu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gt2dxplwhyy.html

[A09] 绝对值与最大最小值
来源：http://dali.hysaishi.cn/Article/details/gt2ktofuhls.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2foxmphdi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2iolrebie.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2bxekezfm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.iojbl.cn/Article/details/gt2warnbjag.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2mmbmuhwz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.mhx1999.top/Article/details/gt2itqzvcot.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cashguo.top/Article/details/gt2gzokntiv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2lptntist.html

[A10] 生成随机数
来源：http://dali.jyoumei.cn/Article/details/gt2clnrkjyp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258888.top/Article/details/gt2hyecjxpf.html

PHP:  random_int(1, 100);
来源：http://dali.hnxiangtu.top/Article/details/gt2zrqcjnik.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gt2gepjxvxs.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gaohongyu789.top/Article/details/gt2vdjxeplz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yangfankeji.com/Article/details/gt2vqkbvvwn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhengqikj.top/Article/details/gt2jsuhzeso.html

Ruby: rand(1..100)
来源：http://dali.yj202588.top/Article/details/gt2fkkezhiz.html

C#:   new Random().Next(1, 101)
来源：http://dali.aizwys.cn/Article/details/gt2fzxvziem.html

[A11] 条件表达式（三元）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjyiputm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yj202588.top/Article/details/gt2xuyqlere.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gt2oltowttn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gt2piybfkxt.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfxgyihj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gt2jfthtgqs.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.havefunace.top/Article/details/gt2rkwslqew.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gt2tcqcnalm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gt2cepzbzdf.html

[A12] 字符串插值 / 格式化
来源：http://dali.chenlongwang.top/Article/details/gt2rsfezmac.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2yduasngl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.tian-w.cn/Article/details/gt2xnxbtcjy.html

JS:   `Hello, ${name}!`
来源：http://dali.daxiang520.top/Article/details/gt2siyajgbz.html

TS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gt2nhgafhtv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gt2fvacyuyz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ivvv.top/Article/details/gt2frcjabvj.html

Ruby: "Hello, #{name}!"
来源：http://dali.bjfxy.top/Article/details/gt2mderjnox.html

C#:   $"Hello, {name}!"
来源：http://dali.jqgfzy.top/Article/details/gt2acmytvge.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.andypj.xyz/Article/details/gt2wdbuisah.html

Py:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iftcniew.html

PHP:  "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjqevshh.html

JS:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzpeeefk.html

TS:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2kgkwzmqh.html

Java: "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gt2uayfjgzt.html

Go:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gt2rkcugxyd.html

Ruby: "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2riadalbe.html

C#:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2eeguldnw.html

[A14] 注释写法
来源：http://dali.redwolf501.top/Article/details/gt2aetghosm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.andypj.xyz/Article/details/gt2mzorkihi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gt2wqahwebh.html

JS:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gt2fakjxqpk.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gt2jrsfbues.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.fzhhl.top/Article/details/gt2cjjrdafk.html

Go:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gt2rkyplbis.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sweek.top/Article/details/gt2uqcktvql.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgfanfgw.html

[A15] 空值判断与默认值
来源：http://dali.aibaodan.cn/Article/details/gt2wqtfbxcc.html

Py:   value = data or "默认值"
来源：http://dali.iojbl.cn/Article/details/gt2wxfkhkag.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gt2riweijce.html

JS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gt2kknuboaw.html

TS:   const value = data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gt2fcztomqi.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ehwqpu.com/Article/details/gt2onaspwad.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sxryk.cn/Article/details/gt2uoltexoj.html

Ruby: value = data || "默认值"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2turhonuq.html

C#:   var value = data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gt2tantyzfd.html

[A16] 真假值判断规则
来源：http://dali.xinyue.icu/Article/details/gt2pqbuikcn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.dashuyun.cn/Article/details/gt2xysyszec.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.bjfxy.top/Article/details/gt2frmxgirt.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gaohongyu789.top/Article/details/gt2mqmjwvap.html

TS:   if (!x) {}
来源：http://dali.andypj.xyz/Article/details/gt2ytxakdok.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ybcxt.top/Article/details/gt2dahqgkcq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evqlptiw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ehwqpu.com/Article/details/gt2podohmnm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.316326.xyz/Article/details/gt2qdxjmtzm.html

[A17] 位运算
来源：http://dali.smart0.xyz/Article/details/gt2zhjnfrsj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gt2ixowqggc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cheryme.top/Article/details/gt2okiqgutg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gt2nqajpjsg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxcjyqth.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gt2emwyvlkh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gt2lutktwai.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2slotgolx.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2gxvnidvk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.redwolf501.top/Article/details/gt2xetnkfqu.html

Py:   ord("A"); chr(65)
来源：http://dali.yanxiufei.cn/Article/details/gt2ikpdsflw.html

PHP:  ord("A"); chr(65)
来源：http://dali.sysykeji.top/Article/details/gt2qpnuvjfe.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.snrcjt.cn/Article/details/gt2ecxeqbth.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gt2jkrzxmnb.html

Java: (int) 'A'; (char) 65
来源：http://dali.birdmap.top/Article/details/gt2aoihlbas.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yongpay.top/Article/details/gt2gkstomhk.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdluiatk.html

C#:   (int)'A'; (char)65
来源：http://dali.9152youxi.cn/Article/details/gt2ozhrqhiz.html

[A19] 交换两个变量
来源：http://dali.daria6918.cn/Article/details/gt2eolmrxyv.html

Py:   a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gt2bwflbsri.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jianghu66.top/Article/details/gt2bgrmznam.html

JS:   [a, b] = [b, a];
来源：http://dali.meibo888.top/Article/details/gt2qgxqhvct.html

TS:   [a, b] = [b, a];
来源：http://dali.aibaodan.cn/Article/details/gt2eukgxbjo.html

Java: int t = a; a = b; b = t;
来源：http://dali.tanke756.top/Article/details/gt2gcngxjlg.html

Go:   a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gt2ibiuiixw.html

Ruby: a, b = b, a
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbrmenxn.html

C#:   (a, b) = (b, a);
来源：http://dali.sufxvd.cn/Article/details/gt2mnrxtilx.html

[A20] 读取标准输入
来源：http://dali.zhengqikj.top/Article/details/gt2erjerrnz.html

Py:   name = input("请输入：")
来源：http://dali.yj20258888.top/Article/details/gt2udxmdjgs.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nwbrower.top/Article/details/gt2lcirvzzu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yvedp.cn/Article/details/gt2eysuglzv.html

TS:   // Node.js：readline 模块
来源：http://dali.nwbrower.top/Article/details/gt2tpieylkx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yanxiufei.cn/Article/details/gt2ybdgdwld.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.fzhhl.top/Article/details/gt2azzevgeg.html

Ruby: gets.chomp
来源：http://dali.iojbl.cn/Article/details/gt2iwhbkljz.html

C#:   Console.ReadLine();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddsmnntp.html

[A21] 保留指定小数位输出
来源：http://dali.guowangkeji.top/Article/details/gt2uquzcvhq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrqyimww.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gt2jngusezn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gt2tlzaelbd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlwxzshw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gt2nzdmgcic.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gt2porlnail.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wprmcnos.html

C#:   3.14159.ToString("F2")
来源：http://dali.ehwqpu.com/Article/details/gt2vsedgsbp.html

[A22] 获取字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2nvqrugaz.html

Py:   len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kaaltirk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sxryk.cn/Article/details/gt2fbcjokuf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqpdrild.html

TS:   s.length
来源：http://dali.svipenyu.cn/Article/details/gt2pygyaqxx.html

Java: s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxtqmsvi.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xuanzx.com/Article/details/gt2oubeddqz.html

Ruby: s.length
来源：http://dali.shzxlz.cn/Article/details/gt2qohfwffn.html

C#:   s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2gwkklxai.html

[A23] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2itaquica.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gotoacloud.top/Article/details/gt2ainlpofa.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hnxiangtu.top/Article/details/gt2cmwuoltf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gt2crlpwnsk.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gt2qstyrmma.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uusuekcg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cashguo.top/Article/details/gt2aqsqztxr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.aizwys.cn/Article/details/gt2cpmxozap.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cucudq.cn/Article/details/gt2rinxitkd.html

[A24] 去除首尾空白
来源：http://dali.kuanghao11.cn/Article/details/gt2zgdnurzg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gzhubu.top/Article/details/gt2vnusuicj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yuanzhike.top/Article/details/gt2odnhkwec.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cheryme.top/Article/details/gt2shzjfoyp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yonumen.top/Article/details/gt2kkohmppa.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yonumen.top/Article/details/gt2ljmfraua.html

Go:   strings.TrimSpace(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjvtxkgs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cheryme.top/Article/details/gt2gthamkpn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigufen.top/Article/details/gt2xwfcksjr.html

[A25] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2ybllubcp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gt2xgkiwlur.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jyoumei.cn/Article/details/gt2ywgsfixq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ihhfjhkf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gzhubu.top/Article/details/gt2eibwwrnh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nwbrower.top/Article/details/gt2bwumlbnf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gt2emwebphe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yongpay.top/Article/details/gt2ocaamwro.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hammf.cn/Article/details/gt2bhrsaiff.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvolhpwe.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenlongwang.top/Article/details/gt2jcjbxhkp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cashguo.top/Article/details/gt2lpcmrqqq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.wangdashe.top/Article/details/gt2niykcgie.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tianlin.xyz/Article/details/gt2iculgnvb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sufxvd.cn/Article/details/gt2ysxtzkmd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangdashe.top/Article/details/gt2ciogarom.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cashguo.top/Article/details/gt2exwchbrk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gt2sqvszntp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ucgondxq.html

B. 流程控制
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsbixrbn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2dqorzkwt.html

[B01] 条件判断 if / else
来源：http://dali.dashuyun.cn/Article/details/gt2akuikbaj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daria6918.cn/Article/details/gt2pchfakjp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sxryk.cn/Article/details/gt2lberiqjx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gt2asrzidsx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gt2jyifpsqq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2xnccrigv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuanzhike.top/Article/details/gt2kcuhyqyk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2atmsinng.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gt2aqtlvviv.html

[B02] 多分支 else if / elif
来源：http://dali.shangyingyoupin.top/Article/details/gt2xybwnfon.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinqigfzy.top/Article/details/gt2mwsglejw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ehwqpu.com/Article/details/gt2mnsdricp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gt2jnrezsuc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2bmlcrpoh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gt2qphwrxrn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ybcxt.top/Article/details/gt2mrofehrh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.havefunace.top/Article/details/gt2wbacorqk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gt2pvsecpoq.html

[B03] switch / match / case
来源：http://dali.nwbrower.top/Article/details/gt2qegwonrs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guannengcc.top/Article/details/gt2okjrrikd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqusixhk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gt2lvrutorf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ggyajdcb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gt2ybnntdbr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyqrofaa.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gt2pbtnwtjq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xziqi.cn/Article/details/gt2qatjpyse.html

[B04] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gt2uwzdcxas.html

Py:   for i in range(10): print(i)
来源：http://dali.birdmap.top/Article/details/gt2emocnjhy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinqigufen.top/Article/details/gt2zmnhmtan.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gt2csbljddd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.andypj.xyz/Article/details/gt2mwxojett.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2xkwnamue.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.quarkkingdee.top/Article/details/gt2ujtdqflt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnqzz.top/Article/details/gt2dxcrvkzc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gzhubu.top/Article/details/gt2irpjnbsb.html

[B05] 遍历数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gt2dghvockh.html

Py:   for item in arr: print(item)
来源：http://dali.zhixingplan.top/Article/details/gt2nspbwruv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258888.top/Article/details/gt2uecpaxrk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gt2cbljrbgc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gt2brgbpixp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2mfrulzua.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cdnleiting.top/Article/details/gt2vbpdujme.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenzaomai.com/Article/details/gt2ckhtuorf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jianghu66.top/Article/details/gt2nratvbnp.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gt2hkhfuhxy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dashuyun.cn/Article/details/gt2vvqvcanu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj202588.top/Article/details/gt2yenhyfqp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sxryk.cn/Article/details/gt2oyoepcac.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gt2fooxmrku.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jyoumei.cn/Article/details/gt2npjkewng.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258888.top/Article/details/gt2xkpdmnue.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258.top/Article/details/gt2fdtlrsyh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.quarkkingdee.top/Article/details/gt2zbdpdmxh.html

[B07] while 循环
来源：http://dali.gzhubu.top/Article/details/gt2itokoubr.html

Py:   while i < 10: i += 1
来源：http://dali.hfpthk.cn/Article/details/gt2bdbfgdzp.html


<!-- 参考信息 -->