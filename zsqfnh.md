代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.jinqigufen.top/Article/details/gt2ubctzeub.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sxryk.cn/Article/details/gt2rehjjvob.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sxryk.cn/Article/details/gt2xunozbnc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tanke756.top/Article/details/gt2rqvsrogu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.snrcjt.cn/Article/details/gt2hcrqrjyv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gt2jnypkbyy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxomadmx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdmxlyq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gt2ccotulhl.html

[A03] 常量定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogdxxtxm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jyoumei.cn/Article/details/gt2nsqjhtwu.html

PHP:  const PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2yzwrimwl.html

JS:   const PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2rljctyiz.html

TS:   const PI: number = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2iafnqdig.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcejgxgo.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gt2jxjonhuy.html

Ruby: PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gockxgof.html

C#:   const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2uyyaihcy.html

[A04] 判断变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayvmmiee.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zycfv.cn/Article/details/gt2kkxnvaxv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2sbqnqiku.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gt2jwdvykjj.html

TS:   typeof x; x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gt2qjubgprn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.bjfxy.top/Article/details/gt2mmdgzrny.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xylfe.cn/Article/details/gt2tdzfupvl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sufxvd.cn/Article/details/gt2rvuaudrf.html

C#:   x.GetType().Name; x is int
来源：http://dali.yonumen.top/Article/details/gt2tqdpyhpr.html

[A05] 整数除法与取模
来源：http://dali.sufxvd.cn/Article/details/gt2rlrpuzba.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gotoacloud.top/Article/details/gt2fyjpblra.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlsajzv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gt2ltdsqzdv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2iqcyzxmw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2iymbxrlg.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2emqbysoe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2jjpscbet.html

C#:   7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gt2mosmrfvz.html

[A06] 字符串转数字
来源：http://dali.fengsongda.top/Article/details/gt2bcdmrerz.html

Py:   int("42"); float("3.14")
来源：http://dali.0kj1m.cn/Article/details/gt2moxickdx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnqzz.top/Article/details/gt2pdpelbtr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ppjwa.cn/Article/details/gt2ynhhbzyo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sxryk.cn/Article/details/gt2dtwqnntj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.smart0.xyz/Article/details/gt2lrjkaycp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.andypj.xyz/Article/details/gt2pjrlgkrq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ydzc1.top/Article/details/gt2yovqgzdq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.316326.xyz/Article/details/gt2ldghdxqh.html

[A07] 数字转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2uenfzegx.html

Py:   str(42)
来源：http://dali.meibo888.top/Article/details/gt2wiywcpeo.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbizuutl.html

JS:   String(42); (42).toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2luwpjbxi.html

TS:   String(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mglrftud.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jiagoushi.top/Article/details/gt2mwjzfjoi.html

Go:   strconv.Itoa(42)
来源：http://dali.xinyue.icu/Article/details/gt2yiitfvhc.html

Ruby: 42.to_s
来源：http://dali.xinyue.icu/Article/details/gt2usutiuwi.html

C#:   42.ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubhqtipl.html

[A08] 取整与四舍五入
来源：http://dali.gaohongyu789.top/Article/details/gt2qrycieuc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gt2kpyvfxus.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gotoacloud.top/Article/details/gt2dqbdrveg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gt2uvocalzg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hfpthk.cn/Article/details/gt2ahqjhhdq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gt2feqyjaqg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gt2jivsrevn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jqgfzy.top/Article/details/gt2iupawxvk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gt2hnzzlaul.html

[A09] 绝对值与最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aeqmsyui.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2oiygytsw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2kyuufshd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2gcyxiqpn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2czxlbihe.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2syieinnv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.quarkkingdee.top/Article/details/gt2vkcivcrv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.birdmap.top/Article/details/gt2lewvwquv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2ewipbbar.html

[A10] 生成随机数
来源：http://dali.yuxming.cn/Article/details/gt2pwbhezty.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhoulong.xyz/Article/details/gt2abzhpsfl.html

PHP:  random_int(1, 100);
来源：http://dali.cashguo.top/Article/details/gt2pxtgzbge.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ybcxt.top/Article/details/gt2sdjwlwxt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hducnsof.html

Java: new Random().nextInt(100) + 1
来源：http://dali.redwolf501.top/Article/details/gt2fgcoczdq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xziqi.cn/Article/details/gt2ytbzsghm.html

Ruby: rand(1..100)
来源：http://dali.hammf.cn/Article/details/gt2jwkegdup.html

C#:   new Random().Next(1, 101)
来源：http://dali.xinyue.icu/Article/details/gt2vbxmjbcx.html

[A11] 条件表达式（三元）
来源：http://dali.haohaochexian.top/Article/details/gt2hrihbuky.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ivvv.top/Article/details/gt2dwegoltl.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gt2zyhbkwfq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjgrhjji.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gt2mufeiroj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gt2nhbkrjhh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.vqdsnc.cn/Article/details/gt2kvnjylbn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtqhvlpe.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gt2jocxxjat.html

[A12] 字符串插值 / 格式化
来源：http://dali.yvedp.cn/Article/details/gt2vvmzugnu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.iojbl.cn/Article/details/gt2fvpnscio.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ybcxt.top/Article/details/gt2gqeewxxq.html

JS:   `Hello, ${name}!`
来源：http://dali.aibaodan.cn/Article/details/gt2bdsohlux.html

TS:   `Hello, ${name}!`
来源：http://dali.sweek.top/Article/details/gt2eqvgmeww.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.daria6918.cn/Article/details/gt2oszytqfm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2onxjfyjk.html

Ruby: "Hello, #{name}!"
来源：http://dali.ivvv.top/Article/details/gt2iwezwhtc.html

C#:   $"Hello, {name}!"
来源：http://dali.yj20258888.top/Article/details/gt2hztleupt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cdnleiting.top/Article/details/gt2wdxbotnu.html

Py:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2phlurlsh.html

PHP:  "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2eibwgmdb.html

JS:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2efwjjehh.html

TS:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gt2urogtnnf.html

Java: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2hlgiqklr.html

Go:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2ppysjjgj.html

Ruby: "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gt2qbnulsdr.html

C#:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2jsnlskjf.html

[A14] 注释写法
来源：http://dali.birdmap.top/Article/details/gt2ltcytriu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenzaomai.com/Article/details/gt2iafhyiqn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gt2xqenwmng.html

JS:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gt2btgkhgls.html

TS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgmfltpd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.316326.xyz/Article/details/gt2dgmwgvvb.html

Go:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2gumazpsj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppttwrek.html

C#:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gt2itoabbzg.html

[A15] 空值判断与默认值
来源：http://dali.havefunace.top/Article/details/gt2obkjtnci.html

Py:   value = data or "默认值"
来源：http://dali.guannengcc.top/Article/details/gt2fdumngpq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gt2swrshepn.html

JS:   const value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gt2oioubwtz.html

TS:   const value = data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxtsgzuo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.fzhhl.top/Article/details/gt2ejgzsxlq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cucudq.cn/Article/details/gt2ytnamyzy.html

Ruby: value = data || "默认值"
来源：http://dali.zhongyouzk.top/Article/details/gt2fgnxxbfx.html

C#:   var value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gt2iyhtlayu.html

[A16] 真假值判断规则
来源：http://dali.sysykeji.top/Article/details/gt2gzwyphok.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.c1oappe.top/Article/details/gt2kvezbnoo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jianghu66.top/Article/details/gt2ojtvrkda.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jyoumei.cn/Article/details/gt2nvqolcim.html

TS:   if (!x) {}
来源：http://dali.ybcxt.top/Article/details/gt2xlddtuei.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxlsyixb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ydzc1.top/Article/details/gt2izkqbafa.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ppjwa.cn/Article/details/gt2zkjmbyug.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxinkj.top/Article/details/gt2zajybsql.html

[A17] 位运算
来源：http://dali.aizwys.cn/Article/details/gt2wjasyhdt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfeebydz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2kerzlmbk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2cqqsgxjf.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2vbxdwtvs.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gt2gbqwdzgi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2hcgenqdb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gt2cxcmhexe.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2teaqooep.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilelumja.html

Py:   ord("A"); chr(65)
来源：http://dali.0kj1m.cn/Article/details/gt2ypdgdzde.html

PHP:  ord("A"); chr(65)
来源：http://dali.snrcjt.cn/Article/details/gt2bvdadcan.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnxiangtu.top/Article/details/gt2emlpfqie.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tian-w.cn/Article/details/gt2duwjqhcb.html

Java: (int) 'A'; (char) 65
来源：http://dali.yuanzhike.top/Article/details/gt2lpxaydda.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.wangdashe.top/Article/details/gt2cbwelyyi.html

Ruby: "A".ord; 65.chr
来源：http://dali.gzhubu.top/Article/details/gt2nrmjtzml.html

C#:   (int)'A'; (char)65
来源：http://dali.nanxuanxn.top/Article/details/gt2kokxnxek.html

[A19] 交换两个变量
来源：http://dali.jlsjyb.cn/Article/details/gt2gtxeosfk.html

Py:   a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gt2rqmgwbzl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cucudq.cn/Article/details/gt2djtyxioo.html

JS:   [a, b] = [b, a];
来源：http://dali.tianlin.xyz/Article/details/gt2vlwmtkqe.html

TS:   [a, b] = [b, a];
来源：http://dali.zhongyouzk.top/Article/details/gt2slsmdbfc.html

Java: int t = a; a = b; b = t;
来源：http://dali.iojbl.cn/Article/details/gt2tbcbjrhu.html

Go:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilitoeha.html

Ruby: a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gt2wdprqhjg.html

C#:   (a, b) = (b, a);
来源：http://dali.hnqzz.top/Article/details/gt2qlqrzdzc.html

[A20] 读取标准输入
来源：http://dali.smart0.xyz/Article/details/gt2zflrjand.html

Py:   name = input("请输入：")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpodarpp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cdnleiting.top/Article/details/gt2pbtcjxlv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.kuanghao11.cn/Article/details/gt2ogibimuh.html

TS:   // Node.js：readline 模块
来源：http://dali.ybcxt.top/Article/details/gt2xzwefxkf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.smart0.xyz/Article/details/gt2pgdnwbhh.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.smart0.xyz/Article/details/gt2rqyohzef.html

Ruby: gets.chomp
来源：http://dali.yj20258.top/Article/details/gt2xojbekxg.html

C#:   Console.ReadLine();
来源：http://dali.nanxinkj.top/Article/details/gt2hnumcbsa.html

[A21] 保留指定小数位输出
来源：http://dali.fzhhl.top/Article/details/gt2mrelnhfp.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gzhubu.top/Article/details/gt2tmngtcit.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2zbbnfxdc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2rzklnswh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gt2pgupbdaa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhaafvei.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gt2dvyfffrx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gt2rlfwbjeg.html

C#:   3.14159.ToString("F2")
来源：http://dali.xinyue.icu/Article/details/gt2prbkcgly.html

[A22] 获取字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2xnmgcagz.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gt2oymelfvh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.andypj.xyz/Article/details/gt2tmlurqav.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenlongwang.top/Article/details/gt2rrtbknsd.html

TS:   s.length
来源：http://dali.cucudq.cn/Article/details/gt2qxujrwze.html

Java: s.length()
来源：http://dali.aizwys.cn/Article/details/gt2xxxbbtsh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guannengcc.top/Article/details/gt2kcoiqwxo.html

Ruby: s.length
来源：http://dali.hfpthk.cn/Article/details/gt2jhjogrsj.html

C#:   s.Length
来源：http://dali.xylfe.cn/Article/details/gt2xopknqgp.html

[A23] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2bofcfeoa.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gt2nawfojah.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.redwolf501.top/Article/details/gt2tfrztdvx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkqinlth.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gt2jdyydhpg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gt2fvvenwcu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjlmxmgd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.guannengcc.top/Article/details/gt2ymztriub.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jiagoushi.top/Article/details/gt2gmrdtjks.html

[A24] 去除首尾空白
来源：http://dali.quarkkingdee.top/Article/details/gt2agrrzuwo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.pycfn.com/Article/details/gt2vnyxrccm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.haohaochexian.top/Article/details/gt2mvguresw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlmnpmps.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gt2sceatwrm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jiagoushi.top/Article/details/gt2xdzxwcbb.html

Go:   strings.TrimSpace(s)
来源：http://dali.daxiang520.top/Article/details/gt2zdnkwsje.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.andypj.xyz/Article/details/gt2mmavpazb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sxryk.cn/Article/details/gt2gdwgsomc.html

[A25] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2kvqiiymg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.haohaochexian.top/Article/details/gt2zmydgbig.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yvedp.cn/Article/details/gt2efkbsawb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gotoacloud.top/Article/details/gt2ymirsdhi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ipvjhwnj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hysaishi.cn/Article/details/gt2cevratkq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.daxiang520.top/Article/details/gt2hiwhoqpk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cheryme.top/Article/details/gt2xwydrcii.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj20258.top/Article/details/gt2dbzmecqc.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrwownqr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuanzhike.top/Article/details/gt2khjxwksg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfvaxcpw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinqigfzy.top/Article/details/gt2assyiwmq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangdashe.top/Article/details/gt2lohhbjsu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gt2rsoogmot.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yvedp.cn/Article/details/gt2tmlwpvly.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2qmnjxppt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gt2tlhgblva.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkzyujrs.html

B. 流程控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbwpjowc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2knjfwsqp.html

[B01] 条件判断 if / else
来源：http://dali.hnxiangtu.top/Article/details/gt2fnjlfkmb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozugcoxc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jianghu66.top/Article/details/gt2ttldzenz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmcirvrk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gt2vjdglyvz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gt2qcafkbfo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sxryk.cn/Article/details/gt2rizqzkeg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigfzy.top/Article/details/gt2zhixbxii.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gt2fgeedqkv.html

[B02] 多分支 else if / elif
来源：http://dali.andypj.xyz/Article/details/gt2ccdadvzx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkghehdj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdclcmjo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnalxaij.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2qlvxeyqh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjlvcvxf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.birdmap.top/Article/details/gt2suxoazim.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gt2zukhuyxa.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gt2cyuglydz.html

[B03] switch / match / case
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xusdueqc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ydzc1.top/Article/details/gt2saaipcss.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gt2nudebiuy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gt2ocrllrue.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gt2evloxvkb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gt2arymeoqv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tycbvudo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.c1oappe.top/Article/details/gt2hxhjlnqr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gt2kfsvoloz.html

[B04] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gt2tgwjdjej.html

Py:   for i in range(10): print(i)
来源：http://dali.aibaodan.cn/Article/details/gt2tfztsqze.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.andypj.xyz/Article/details/gt2ovulduuw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gt2wcvuhjrj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2augogeoj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pupebyip.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gaohongyu789.top/Article/details/gt2bbvhpdyw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daxiang520.top/Article/details/gt2snypvruu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sxryk.cn/Article/details/gt2eljuwyzn.html

[B05] 遍历数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gt2reztyxvq.html

Py:   for item in arr: print(item)
来源：http://dali.yvedp.cn/Article/details/gt2hyarirav.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hufemrji.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gt2otwzgpdj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gt2engljuvm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aizwys.cn/Article/details/gt2fgbzukkh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqnvfywn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqctegzc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhixingplan.top/Article/details/gt2qcxdqekm.html

[B06] 遍历字典 / 对象
来源：http://dali.xziqi.cn/Article/details/gt2ivxbrgkk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jyoumei.cn/Article/details/gt2demyrbzx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guannengcc.top/Article/details/gt2lvvausyf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj202588.top/Article/details/gt2pjxrpyfo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imluppqn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pycfn.com/Article/details/gt2flyvspmc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aizwys.cn/Article/details/gt2cicprcdd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangdashe.top/Article/details/gt2ummtsyib.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258888.top/Article/details/gt2kerwhzsf.html

[B07] while 循环
来源：http://dali.ppjwa.cn/Article/details/gt2vaqeljfb.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigufen.top/Article/details/gt2fgzhdvyh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esjmusje.html

JS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2hqiudeib.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgewtvjg.html

Java: while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gffykqis.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhoulong.xyz/Article/details/gt2vueqwodu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gt2pdnqhvcm.html

C#:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gt2agkvklmb.html

[B08] do-while（至少执行一次）
来源：http://dali.yuxming.cn/Article/details/gt2ttnyqrkn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.meibo888.top/Article/details/gt2ekyoxwsr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2cweswtxo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gt2normazex.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2dpviliny.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rsoyxbnf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gt2ppwxqcqu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.havefunace.top/Article/details/gt2ywgxeprc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2qezdozdu.html


<!-- 参考信息 -->