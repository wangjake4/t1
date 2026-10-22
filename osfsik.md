代发 wailian999

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yanxiufei.cn/Article/details/gt2vvqzjsil.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xziqi.cn/Article/details/gt2zmxqrikk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sfbyrfxu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhengqikj.top/Article/details/gt2iwmogavk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shzxlz.cn/Article/details/gt2rjmmptij.html

[A07] 数字转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2fnpdvcwa.html

Py:   str(42)
来源：http://dali.316326.xyz/Article/details/gt2ycgqboeo.html

PHP:  (string) 42; strval(42)
来源：http://dali.cheryme.top/Article/details/gt2wgobmlfz.html

JS:   String(42); (42).toString()
来源：http://dali.nanxinkj.top/Article/details/gt2unzuilat.html

TS:   String(42)
来源：http://dali.zdqjudy.top/Article/details/gt2khyoaskq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrkyhknd.html

Go:   strconv.Itoa(42)
来源：http://dali.yj20258888.top/Article/details/gt2cohwwlva.html

Ruby: 42.to_s
来源：http://dali.fzhhl.top/Article/details/gt2bgenygdr.html

C#:   42.ToString()
来源：http://dali.chenzaomai.com/Article/details/gt2euuvyodh.html

[A08] 取整与四舍五入
来源：http://dali.jyoumei.cn/Article/details/gt2shkjapcq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gt2vfetztvs.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ulequumj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2ppfkootw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shzxlz.cn/Article/details/gt2vemnmmzv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gt2cckosspv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gt2ntdskrxk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigufen.top/Article/details/gt2ldymkwyd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gt2ujnsjuub.html

[A09] 绝对值与最大最小值
来源：http://dali.jinqigufen.top/Article/details/gt2rfdckrca.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2jddezlxf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2lrusdfhe.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2kmiepdto.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2dabgygnw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2nwrrxxvf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.redwolf501.top/Article/details/gt2dzkoctmb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzyejjmd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2hajbgoml.html

[A10] 生成随机数
来源：http://dali.yanxiufei.cn/Article/details/gt2iwopakbk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yonumen.top/Article/details/gt2wwsogiya.html

PHP:  random_int(1, 100);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrcvlzon.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gt2vcotligj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yongpay.top/Article/details/gt2ixcebzpu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guannengcc.top/Article/details/gt2vrxgpstl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yanxiufei.cn/Article/details/gt2akezapde.html

Ruby: rand(1..100)
来源：http://dali.xylfe.cn/Article/details/gt2farrvrwh.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj202588.top/Article/details/gt2uferokfe.html

[A11] 条件表达式（三元）
来源：http://dali.bjfxy.top/Article/details/gt2nnzbnhhw.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.svipenyu.cn/Article/details/gt2sympypaa.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gt2pkqshygj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2yfherjaz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gt2kvvctqhd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gt2ctruyolk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zycfv.cn/Article/details/gt2wqaikvbt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gt2oreqripo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gt2uumphxig.html

[A12] 字符串插值 / 格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2noyukjpd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.c1oappe.top/Article/details/gt2fcwyciyj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zycfv.cn/Article/details/gt2pqdpgwky.html

JS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzzvwqml.html

TS:   `Hello, ${name}!`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdynxdjh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cqqwz.cn/Article/details/gt2hxgkwxkx.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jianghu66.top/Article/details/gt2gabgxhmo.html

Ruby: "Hello, #{name}!"
来源：http://dali.shzxlz.cn/Article/details/gt2wxavfvzk.html

C#:   $"Hello, {name}!"
来源：http://dali.chenlongwang.top/Article/details/gt2qwnongfj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.havefunace.top/Article/details/gt2fjqhoraz.html

Py:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2flbpgkkl.html

PHP:  "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2yndocnor.html

JS:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gt2rrskpxtw.html

TS:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2wmksogwl.html

Java: "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpprgcvg.html

Go:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gt2qmnnpmov.html

Ruby: "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2iysrimvo.html

C#:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gt2wkwnmaty.html

[A14] 注释写法
来源：http://dali.bjfxy.top/Article/details/gt2puygxtev.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhiwuduotai.top/Article/details/gt2eczefoew.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gt2mfocflyv.html

JS:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gt2dzcmvtus.html

TS:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gt2twmomgfz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.havefunace.top/Article/details/gt2yupgxpet.html

Go:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gt2tlzfdlrf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cheryme.top/Article/details/gt2caneqinw.html

C#:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gt2pxuhpfpx.html

[A15] 空值判断与默认值
来源：http://dali.cqqwz.cn/Article/details/gt2soopyswn.html

Py:   value = data or "默认值"
来源：http://dali.hnqzz.top/Article/details/gt2zitglnqr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gt2ohozpahb.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gt2iytxiyug.html

TS:   const value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gt2enabvtjs.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cheryme.top/Article/details/gt2woubwufe.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cdnleiting.top/Article/details/gt2ebyyzfjx.html

Ruby: value = data || "默认值"
来源：http://dali.0kj1m.cn/Article/details/gt2efobjefu.html

C#:   var value = data ?? "默认值";
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzucnypp.html

[A16] 真假值判断规则
来源：http://dali.fengsongda.top/Article/details/gt2ixqsovjs.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nwbrower.top/Article/details/gt2dkxovgtb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhengqikj.top/Article/details/gt2opydslrp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hfpthk.cn/Article/details/gt2pvagdqdx.html

TS:   if (!x) {}
来源：http://dali.yvedp.cn/Article/details/gt2cnqamuhp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.mhx1999.top/Article/details/gt2kssxauvo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.smart0.xyz/Article/details/gt2nbzabony.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hysaishi.cn/Article/details/gt2vxsyjlyd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2bgailwfm.html

[A17] 位运算
来源：http://dali.gogol.net.cn/Article/details/gt2upfqjsfi.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2dslaiert.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2ecqbkigw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2vtockbti.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipqpgnux.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gt2wvffrukh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2uippxtla.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2pitdtega.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpejrcdz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkzwnisa.html

Py:   ord("A"); chr(65)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhfgilsy.html

PHP:  ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gt2ugljeooj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.smart0.xyz/Article/details/gt2epdbrpow.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sratjnzw.html

Java: (int) 'A'; (char) 65
来源：http://dali.cheryme.top/Article/details/gt2qkdiiugq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.andypj.xyz/Article/details/gt2xvbdelud.html

Ruby: "A".ord; 65.chr
来源：http://dali.yanxiufei.cn/Article/details/gt2ybhxdnmw.html

C#:   (int)'A'; (char)65
来源：http://dali.chenzaomai.com/Article/details/gt2yrzbiykq.html

[A19] 交换两个变量
来源：http://dali.redwolf501.top/Article/details/gt2auhbzvyd.html

Py:   a, b = b, a
来源：http://dali.yj202588.top/Article/details/gt2ioecsdfn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinqigufen.top/Article/details/gt2yrbccgwn.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258888.top/Article/details/gt2bjtixnzv.html

TS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gt2eoyeyqyb.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuitgbs.html

Go:   a, b = b, a
来源：http://dali.zhongyouzk.top/Article/details/gt2zdwtslll.html

Ruby: a, b = b, a
来源：http://dali.shangyingyoupin.top/Article/details/gt2cljhoges.html

C#:   (a, b) = (b, a);
来源：http://dali.aibaodan.cn/Article/details/gt2sayssytc.html

[A20] 读取标准输入
来源：http://dali.hywenlv.cn/Article/details/gt2vhzougsh.html

Py:   name = input("请输入：")
来源：http://dali.wangshuangyany.cn/Article/details/gt2etdihsxi.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.c1oappe.top/Article/details/gt2mdqshrqm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.c1oappe.top/Article/details/gt2wccodjoh.html

TS:   // Node.js：readline 模块
来源：http://dali.ehwqpu.com/Article/details/gt2alnfzrcb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.kuanghao11.cn/Article/details/gt2mqsyztrq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zdqjudy.top/Article/details/gt2cgvwhpon.html

Ruby: gets.chomp
来源：http://dali.xylfe.cn/Article/details/gt2eyjuuhht.html

C#:   Console.ReadLine();
来源：http://dali.iojbl.cn/Article/details/gt2vwhvaqft.html

[A21] 保留指定小数位输出
来源：http://dali.nanxuanxn.top/Article/details/gt2dvnwaamv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shuidangran.top/Article/details/gt2oeuxvhlc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gt2spkruuda.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gt2rcpjaruf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gt2orwdivev.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gt2ezbgumjv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gt2fqgjxcjo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gt2wilefdmh.html

C#:   3.14159.ToString("F2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrlbduve.html

[A22] 获取字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2dogbnier.html

Py:   len(s)
来源：http://dali.xinyue.icu/Article/details/gt2ulkqhoco.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gzhubu.top/Article/details/gt2odhumwud.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sufxvd.cn/Article/details/gt2tyywcneo.html

TS:   s.length
来源：http://dali.tanke756.top/Article/details/gt2vxzvggmi.html

Java: s.length()
来源：http://dali.tian-w.cn/Article/details/gt2pvzvdszc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdmzqnhw.html

Ruby: s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2cejkojiq.html

C#:   s.Length
来源：http://dali.nwbrower.top/Article/details/gt2cuyxewyw.html

[A23] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2iveioirz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hammf.cn/Article/details/gt2fycrjrfv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jiagoushi.top/Article/details/gt2viiysyru.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzttgzxn.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fengsongda.top/Article/details/gt2okcvticr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbzedjic.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sweek.top/Article/details/gt2dpjmsnrh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258.top/Article/details/gt2fnxexvfi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.quarkkingdee.top/Article/details/gt2jzzuraha.html

[A24] 去除首尾空白
来源：http://dali.meibo888.top/Article/details/gt2cvyycxup.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.tanke756.top/Article/details/gt2owifmhyk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.9152youxi.cn/Article/details/gt2vcksmomo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fsftxuhg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2eazkyuyw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbjtoxzv.html

Go:   strings.TrimSpace(s)
来源：http://dali.hywenlv.cn/Article/details/gt2qkfgvxle.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cucudq.cn/Article/details/gt2zsdfqpqn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bciuiqqk.html

[A25] 字符串比较
来源：http://dali.hammf.cn/Article/details/gt2etheplfi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jlsjyb.cn/Article/details/gt2lzeshzgc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzyrdwiy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wdtsyluf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2ytfppkvl.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nanxinkj.top/Article/details/gt2ibjmegmc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sysykeji.top/Article/details/gt2gpjtodzg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hywenlv.cn/Article/details/gt2hrmqwire.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zdqjudy.top/Article/details/gt2djkkjtnr.html

[A26] 类型转换总览
来源：http://dali.nanxinkj.top/Article/details/gt2duxuwnph.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.haohaochexian.top/Article/details/gt2cmxzossu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zycfv.cn/Article/details/gt2batjmmgw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenzaomai.com/Article/details/gt2dwjlwcad.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jianghu66.top/Article/details/gt2lfhpbftp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.birdmap.top/Article/details/gt2ptqvjvbx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sxryk.cn/Article/details/gt2dggreiph.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cucudq.cn/Article/details/gt2hyhmmjgs.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gt2liiyvmmi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2sycrchfn.html

B. 流程控制
来源：http://dali.aizwys.cn/Article/details/gt2vbqegpgg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2uszakfah.html

[B01] 条件判断 if / else
来源：http://dali.meibo888.top/Article/details/gt2wixbxghc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ppjwa.cn/Article/details/gt2hlhtzuwn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pycfn.com/Article/details/gt2gitjtrgd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gt2lkdpaspd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llynrruy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gt2jgcdqheu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgrzgfuo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hysaishi.cn/Article/details/gt2tcsgiycg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzsowtgq.html

[B02] 多分支 else if / elif
来源：http://dali.gogol.net.cn/Article/details/gt2oxqcgzkj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sxryk.cn/Article/details/gt2bvtjctim.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.havefunace.top/Article/details/gt2rlpjytyg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gt2xudteitt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gt2xvekjspe.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gt2llqeeoxg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tianlin.xyz/Article/details/gt2uzuxubjf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sweek.top/Article/details/gt2wbvqfgrz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2hqqphqaq.html

[B03] switch / match / case
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iciaozxp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmkxcko.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhizrcor.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gt2hoiwhvcs.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gt2zfhpdgxa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gt2vsezzqci.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gt2jsqdgxpj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.kuanghao11.cn/Article/details/gt2tzuckikt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlkvjzst.html

[B04] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2pqqpndhj.html

Py:   for i in range(10): print(i)
来源：http://dali.zycfv.cn/Article/details/gt2tkwyieff.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dashuyun.cn/Article/details/gt2vvjotfjc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwqrurop.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gt2zumsoynd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xziqi.cn/Article/details/gt2iofkgouw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hammf.cn/Article/details/gt2tsdzdjjd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.birdmap.top/Article/details/gt2njdeiqql.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cheryme.top/Article/details/gt2ghlvptjs.html

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dpmamtrb.html

Py:   for item in arr: print(item)
来源：http://dali.zdqjudy.top/Article/details/gt2pcdueuvh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gt2lvzblcbf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gt2udkmpezj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gt2qmviqzpe.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgrposhr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cdnleiting.top/Article/details/gt2lcixkmuv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ppjwa.cn/Article/details/gt2wksdgmjz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhengqikj.top/Article/details/gt2smsirmct.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gt2lymxobzi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.smart0.xyz/Article/details/gt2chlahqhg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.daria6918.cn/Article/details/gt2qkyijnud.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gt2ngbslsag.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gt2wsqyzein.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2khqxkmyj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.redwolf501.top/Article/details/gt2zavfmfop.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenlongwang.top/Article/details/gt2gcwpngno.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ppjwa.cn/Article/details/gt2ktooydjh.html

[B07] while 循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udccerqc.html

Py:   while i < 10: i += 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpwovydy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gzhubu.top/Article/details/gt2cusvskja.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2bawuwxss.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tdrvrgqi.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2byrlacfq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gt2tcsoclts.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xylfe.cn/Article/details/gt2jhfzamoq.html

C#:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gt2whqyolyb.html

[B08] do-while（至少执行一次）
来源：http://dali.haohaochexian.top/Article/details/gt2amosjktb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hywenlv.cn/Article/details/gt2sagjbuka.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.pycfn.com/Article/details/gt2wndanuii.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2cdxizlgi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2dtohzzep.html

Java: do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2qvtnbpch.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gt2hchrgigj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenjidiqi.icu/Article/details/gt2kziboazr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2spvkzjsr.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gt2kgqsxasr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.haohaochexian.top/Article/details/gt2ilbxkfty.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydrjlzey.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2nsxpkscp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2jotroexe.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2btqxkksp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfisxawb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gt2mszzvqea.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2kfldujxu.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gt2hoqnumps.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gt2xqiohish.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gt2unxvgvmo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gt2mssbxaup.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gt2ixyegtla.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gt2xrunynrq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sxryk.cn/Article/details/gt2uparrjci.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hfpthk.cn/Article/details/gt2bbxdqiab.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gt2kjzzeznw.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gt2wzyexrep.html

Py:   list(range(0, 10, 2))
来源：http://dali.iojbl.cn/Article/details/gt2shngokfh.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gt2lzxbssbs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cklfyeti.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gt2sxchfekc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ybcxt.top/Article/details/gt2imnmvhgv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gt2ccwpsqss.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zycfv.cn/Article/details/gt2ngajzvcu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gt2muwurqxw.html

[B12] 跳出多层循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2inauofqn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shzxlz.cn/Article/details/gt2emsvyzan.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dianchejie.cn/Article/details/gt2nutrnfsh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gt2vzuzqkio.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gt2prfwkrfd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gt2rdldbccy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gt2qtfwgrzd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shuidangran.top/Article/details/gt2gfaszzvv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gt2meeiluos.html

[B13] 判断是否为数字
来源：http://dali.gzhubu.top/Article/details/gt2ldouijwp.html

Py:   isinstance(x, (int, float))
来源：http://dali.mhx1999.top/Article/details/gt2mirwkede.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gt2xreksjiy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2hqhqeitz.html


<!-- 参考信息 -->