代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.yvedp.cn/Article/details/gtihtsfodp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tianlin.xyz/Article/details/gtdswzefks.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtepflbfag.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtogzaosvg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cashguo.top/Article/details/gtmdefwbaf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlqihluc.html

Go:   name := "Alex"; age := 20
来源：http://dali.daria6918.cn/Article/details/gtkyqavimp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhiwuduotai.top/Article/details/gtgxmewlll.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtzojbwids.html

[A03] 常量定义
来源：http://dali.ehwqpu.com/Article/details/gtiwbleeki.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dashuyun.cn/Article/details/gtvjbguleq.html

PHP:  const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtqokxmlwg.html

JS:   const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtixzxlxbd.html

TS:   const PI: number = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtofjenxec.html

Java: static final double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtstjohnga.html

Go:   const PI = 3.14159
来源：http://dali.sweek.top/Article/details/gtubrmzmel.html

Ruby: PI = 3.14159
来源：http://dali.meibo888.top/Article/details/gtfdtjcave.html

C#:   const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtyzzvhees.html

[A04] 判断变量类型
来源：http://dali.ydzc1.top/Article/details/gtywzwjgau.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gtrztcungn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xylfe.cn/Article/details/gttlzjvpbi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tanke756.top/Article/details/gtlwbzwyxa.html

TS:   typeof x; x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtqmnvcdhs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gzhubu.top/Article/details/gtavmfzwjl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.feifeiyinyue.top/Article/details/gtdafkfine.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sysykeji.top/Article/details/gtimbwqbfs.html

C#:   x.GetType().Name; x is int
来源：http://dali.jyoumei.cn/Article/details/gtyibbynxy.html

[A05] 整数除法与取模
来源：http://dali.tanke756.top/Article/details/gtzarmwxlo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.iojbl.cn/Article/details/gtdclmuuww.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtjuctxnur.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtswoltrjq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtwhvodhhs.html

Java: 7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtzmymumge.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtnoxjqlmo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtlggllatb.html

C#:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtogwuzzdn.html

[A06] 字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtvcfyaoaj.html

Py:   int("42"); float("3.14")
来源：http://dali.ehwqpu.com/Article/details/gtdmfcysdy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fzhhl.top/Article/details/gteqqeiard.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gtvgqvpyqv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnqzz.top/Article/details/gtbcloihrg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphcoozoh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.haohaochexian.top/Article/details/gtjouflkbd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.vqdsnc.cn/Article/details/gtvbjgryep.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtectdahgs.html

[A07] 数字转字符串
来源：http://dali.redwolf501.top/Article/details/gtkpvzvuay.html

Py:   str(42)
来源：http://dali.chenlongwang.top/Article/details/gtqnbjprdp.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhoulong.xyz/Article/details/gtvyrerxni.html

JS:   String(42); (42).toString()
来源：http://dali.cucudq.cn/Article/details/gtytpbrdqn.html

TS:   String(42)
来源：http://dali.cqqwz.cn/Article/details/gtllsswugk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbufpqrtw.html

Go:   strconv.Itoa(42)
来源：http://dali.jinqigufen.top/Article/details/gtcrppegil.html

Ruby: 42.to_s
来源：http://dali.yj202588.top/Article/details/gtklmonien.html

C#:   42.ToString()
来源：http://dali.yuanzhike.top/Article/details/gtoecktppa.html

[A08] 取整与四舍五入
来源：http://dali.snrcjt.cn/Article/details/gthvtuvzsz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtlqapojvn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnqzz.top/Article/details/gtcrowcfjn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtxdpfmsgx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.tian-w.cn/Article/details/gthsjeyxrn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtjmoyrlui.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gtwzccufol.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhiwuduotai.top/Article/details/gtvlxikpuv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfepipku.html

[A09] 绝对值与最大最小值
来源：http://dali.aizwys.cn/Article/details/gtjwekkoho.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtbhuwtyov.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtwgujkgqt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtrwuqckem.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gttnvrcwwq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtcfkiexzl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhtayaib.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.andypj.xyz/Article/details/gtimchchwd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxcrjrij.html

[A10] 生成随机数
来源：http://dali.nanxuanxn.top/Article/details/gtlsxpupdi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.daria6918.cn/Article/details/gtukymyrvp.html

PHP:  random_int(1, 100);
来源：http://dali.wangshuangyany.cn/Article/details/gtufsyores.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xziqi.cn/Article/details/gtsyuepmlx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfavkbjp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ivvv.top/Article/details/gtoyffhkkk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hywenlv.cn/Article/details/gtajukkzdo.html

Ruby: rand(1..100)
来源：http://dali.yanxiufei.cn/Article/details/gtmiyglnvx.html

C#:   new Random().Next(1, 101)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgouwqgxc.html

[A11] 条件表达式（三元）
来源：http://dali.snrcjt.cn/Article/details/gtcqppfhpa.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jianghu66.top/Article/details/gtupufulhb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtlswhttkz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtuzrkjnkl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtwycbjoat.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtxnxmxjrn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zdqjudy.top/Article/details/gtcicyomdz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihklfpjc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gttnqjruva.html

[A12] 字符串插值 / 格式化
来源：http://dali.havefunace.top/Article/details/gtmkniujsk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hywenlv.cn/Article/details/gtohtycwvc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.aizwys.cn/Article/details/gtlviarkbd.html

JS:   `Hello, ${name}!`
来源：http://dali.xuetiantiany.cn/Article/details/gtcarselzi.html

TS:   `Hello, ${name}!`
来源：http://dali.xuanzx.com/Article/details/gtetddhvxn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aibaodan.cn/Article/details/gtlivkrcwh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yuxming.cn/Article/details/gtanvixcne.html

Ruby: "Hello, #{name}!"
来源：http://dali.nanxinkj.top/Article/details/gtongujezu.html

C#:   $"Hello, {name}!"
来源：http://dali.cdnleiting.top/Article/details/gtiohrbbqs.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cheryme.top/Article/details/gtlkqskznl.html

Py:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtvrptvljw.html

PHP:  "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gthulmfvto.html

JS:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtweksxabl.html

TS:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtaorynelv.html

Java: "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtvwsivzwn.html

Go:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gturgtqjgn.html

Ruby: "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtycdxvsqo.html

C#:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtgrbnrxdj.html

[A14] 注释写法
来源：http://dali.nanxuanxn.top/Article/details/gtmjvrzvho.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.wangshuangyany.cn/Article/details/gtgpwwftke.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtozmeauaq.html

JS:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gtnlojkcuz.html

TS:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gtkxvzamxe.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.iojbl.cn/Article/details/gtayglzbjw.html

Go:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gthkzinlng.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.chenlongwang.top/Article/details/gtkjuxhqcz.html

C#:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtxaixncso.html

[A15] 空值判断与默认值
来源：http://dali.hammf.cn/Article/details/gtuidzyxav.html

Py:   value = data or "默认值"
来源：http://dali.tian-w.cn/Article/details/gtamvooffe.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gtxntzdmaj.html

JS:   const value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gtqiaqdhcw.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtojfxlbji.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gotoacloud.top/Article/details/gtqdnvhfgi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.316326.xyz/Article/details/gtexjjirax.html

Ruby: value = data || "默认值"
来源：http://dali.gogol.net.cn/Article/details/gtlpkledhd.html

C#:   var value = data ?? "默认值";
来源：http://dali.yuanzhike.top/Article/details/gtendkpmpf.html

[A16] 真假值判断规则
来源：http://dali.redwolf501.top/Article/details/gtzhscimre.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yongpay.top/Article/details/gtizztlpjg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gotoacloud.top/Article/details/gthwnmaqvi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.haohaochexian.top/Article/details/gtxbcvetzr.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gtchccrnfv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrhosynfo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zycfv.cn/Article/details/gtbzltadnw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cashguo.top/Article/details/gtbopofpgc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtxnswfrfh.html

[A17] 位运算
来源：http://dali.cashguo.top/Article/details/gtaoyaimbi.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtgujviggb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.havefunace.top/Article/details/gthnaaaebn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtvhteudie.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhxkugcd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtawgjbnfa.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtrakngwnb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtqyklnygh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtaukbpviz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.redwolf501.top/Article/details/gtslkqewed.html

Py:   ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gtndybsqir.html

PHP:  ord("A"); chr(65)
来源：http://dali.xziqi.cn/Article/details/gtbxbvkoyo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.havefunace.top/Article/details/gtgkkyfmvv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tian-w.cn/Article/details/gtpdjdcfdb.html

Java: (int) 'A'; (char) 65
来源：http://dali.shangyingyoupin.top/Article/details/gtsycybdoy.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.andypj.xyz/Article/details/gtmypxblyp.html

Ruby: "A".ord; 65.chr
来源：http://dali.cdnleiting.top/Article/details/gtjubgzagz.html

C#:   (int)'A'; (char)65
来源：http://dali.dianchejie.cn/Article/details/gtkdtbagjb.html

[A19] 交换两个变量
来源：http://dali.nwbrower.top/Article/details/gtwrerbbcx.html

Py:   a, b = b, a
来源：http://dali.sweek.top/Article/details/gtvrrwrnlq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.daria6918.cn/Article/details/gtprlafdgn.html

JS:   [a, b] = [b, a];
来源：http://dali.gaohongyu789.top/Article/details/gteabaapff.html

TS:   [a, b] = [b, a];
来源：http://dali.sufxvd.cn/Article/details/gttlelrqjc.html

Java: int t = a; a = b; b = t;
来源：http://dali.xuetiantiany.cn/Article/details/gtybjuakai.html

Go:   a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gtvlphcltu.html

Ruby: a, b = b, a
来源：http://dali.shangyingyoupin.top/Article/details/gtdyadqlwv.html

C#:   (a, b) = (b, a);
来源：http://dali.jinqigfzy.top/Article/details/gtdqszeqyw.html

[A20] 读取标准输入
来源：http://dali.cucudq.cn/Article/details/gtjzfwbcse.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gtweyuwwhm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yangfankeji.com/Article/details/gtswunjmhu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxnhqwjh.html

TS:   // Node.js：readline 模块
来源：http://dali.dashuyun.cn/Article/details/gtbkkxppjf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.aizwys.cn/Article/details/gtnfxrkyym.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.birdmap.top/Article/details/gtviksdxln.html

Ruby: gets.chomp
来源：http://dali.shzxlz.cn/Article/details/gtbhloovor.html

C#:   Console.ReadLine();
来源：http://dali.jinqigfzy.top/Article/details/gtxwuvtepy.html

[A21] 保留指定小数位输出
来源：http://dali.havefunace.top/Article/details/gtalglcouj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jyoumei.cn/Article/details/gtzxvfwjvw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gtnvmgenwi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtvnkulqsw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtknreehgc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtqqshlisn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtzmsckytj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gtebxzrzdw.html

C#:   3.14159.ToString("F2")
来源：http://dali.sysykeji.top/Article/details/gteobcckwd.html

[A22] 获取字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtwetfrfjm.html

Py:   len(s)
来源：http://dali.sufxvd.cn/Article/details/gtmvatgaso.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xuanzx.com/Article/details/gtchigprct.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yongpay.top/Article/details/gtzvqvkqnp.html

TS:   s.length
来源：http://dali.cashguo.top/Article/details/gtajtnwwxb.html

Java: s.length()
来源：http://dali.gotoacloud.top/Article/details/gtbelcbqou.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zdqjudy.top/Article/details/gthfsotwab.html

Ruby: s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtkcsujqii.html

C#:   s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtsyxrugoz.html

[A23] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtafovaioh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtxhflbyhq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.nanxinkj.top/Article/details/gtntmskyaf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gttdwmqtmc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gtidakpwzm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gtoigitxep.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtyohfgzob.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtlbrkcluv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.0kj1m.cn/Article/details/gtwskcjyke.html

[A24] 去除首尾空白
来源：http://dali.jlsjyb.cn/Article/details/gtyhqqvirn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.iojbl.cn/Article/details/gtetcuazlg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cashguo.top/Article/details/gtpjmrgfbv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuxming.cn/Article/details/gtoqonotes.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtywdhcoll.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jqgufenzy.top/Article/details/gtenkllstv.html

Go:   strings.TrimSpace(s)
来源：http://dali.cqqwz.cn/Article/details/gtrgzbifdw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cucudq.cn/Article/details/gtyjlmpyjx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangdashe.top/Article/details/gtwyvuxlts.html

[A25] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtxmvwaagr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.kuanghao11.cn/Article/details/gtfjcrpkjm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aizwys.cn/Article/details/gttvpnhhqx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtpwrpmdjq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gtlifgixbk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.0kj1m.cn/Article/details/gtuoehtpbc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gtnrbzjepa.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenzaomai.com/Article/details/gtwxgtudme.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gtsitgnvvl.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gtkrjsjsrr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.guannengcc.top/Article/details/gtvorjaysw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.316326.xyz/Article/details/gtlordxzgy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuetiantiany.cn/Article/details/gtrjxibbeo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jianghu66.top/Article/details/gtdebkawts.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.havefunace.top/Article/details/gtjzngjmzg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhongyouzk.top/Article/details/gtgavkubfn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gaohongyu789.top/Article/details/gtgbwtdxwe.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hysaishi.cn/Article/details/gtsuvqzrzm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttemmymnk.html

B. 流程控制
来源：http://dali.nanxuanxn.top/Article/details/gtmsnthsln.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkajaxdx.html

[B01] 条件判断 if / else
来源：http://dali.nwbrower.top/Article/details/gtjrehxzul.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xinyue.icu/Article/details/gtgpfxmlmu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tianlin.xyz/Article/details/gtyqqpoqvr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtdrtjecwf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gthnwsyebf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gthuwqfdwm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zycfv.cn/Article/details/gtakympbse.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ivvv.top/Article/details/gtwqfrkigu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gthurihetk.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258.top/Article/details/gtjwgibinm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuetiantiany.cn/Article/details/gtgetqonnq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gaohongyu789.top/Article/details/gtursnrgox.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtegqmtipo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtgiprxntk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtgzvrwdvf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.wangshuangyany.cn/Article/details/gtlsydwyud.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cashguo.top/Article/details/gtowcckycq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gtngbufcgf.html

[B03] switch / match / case
来源：http://dali.xinyue.icu/Article/details/gtcbzgpwtw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenzaomai.com/Article/details/gtualmdtbi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gttopshyor.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtfmmcofgh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtphpaszcz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtxmszgooh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenlongwang.top/Article/details/gtxwpagltf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.iojbl.cn/Article/details/gtadgjjhdi.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtkxcbpapc.html

[B04] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtmxhkhcre.html

Py:   for i in range(10): print(i)
来源：http://dali.hnxiangtu.top/Article/details/gtgoiaunus.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmtvsccol.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hywenlv.cn/Article/details/gtekbmglmv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gthvmaqasq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jiagoushi.top/Article/details/gtlkwjrokr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hongshengwenyu.top/Article/details/gthrszdhuf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cheryme.top/Article/details/gtmodizrsm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhengqikj.top/Article/details/gtasbdadfo.html

[B05] 遍历数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtkcfsblif.html

Py:   for item in arr: print(item)
来源：http://dali.nanxinkj.top/Article/details/gthltgjmup.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gaohongyu789.top/Article/details/gtpfoqkuyz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtothwzovq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gthlfteaea.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ydzc1.top/Article/details/gtyqwkadzj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yongpay.top/Article/details/gtcedvadvw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gthxnzltwf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cheryme.top/Article/details/gtmtnzisck.html

[B06] 遍历字典 / 对象
来源：http://dali.jyoumei.cn/Article/details/gtyhgerpmt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shangyingyoupin.top/Article/details/gtbpdvydxg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.svipenyu.cn/Article/details/gtkxawpmzg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gtmokxriro.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtdcxltnyc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fengsongda.top/Article/details/gtyqiiakrp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yongpay.top/Article/details/gtafulkpak.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hfpthk.cn/Article/details/gtywniptpt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shuidangran.top/Article/details/gtwbfvsilg.html

[B07] while 循环
来源：http://dali.dianchejie.cn/Article/details/gthbrlwkwr.html

Py:   while i < 10: i += 1
来源：http://dali.fzhhl.top/Article/details/gtpseapupm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnqzz.top/Article/details/gtrqirxjsw.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtbpoxmort.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtydpxxufl.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtovkuytoy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xziqi.cn/Article/details/gtwccezpbk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangtech.top/Article/details/gttjqkehuk.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtnittbgjz.html

[B08] do-while（至少执行一次）
来源：http://dali.kuanghao11.cn/Article/details/gtarhnddus.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daria6918.cn/Article/details/gtnkbvpzyi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtsqfocjna.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtljnrkhhl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxppmrqdk.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtxjdvqbye.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.aizwys.cn/Article/details/gtlotidnut.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gzhubu.top/Article/details/gtilqpcssw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtcwxztrff.html


<!-- 参考信息 -->