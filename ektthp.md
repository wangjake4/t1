代发 wailian999

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.316326.xyz/Article/details/gt2vngnitve.html

[A07] 数字转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2swydrwzf.html

Py:   str(42)
来源：http://dali.zhoulong.xyz/Article/details/gt2hymszgeu.html

PHP:  (string) 42; strval(42)
来源：http://dali.ydzc1.top/Article/details/gt2qencantc.html

JS:   String(42); (42).toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2jhptqrcn.html

TS:   String(42)
来源：http://dali.cqqwz.cn/Article/details/gt2ooylejfg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gaohongyu789.top/Article/details/gt2rrbdzcge.html

Go:   strconv.Itoa(42)
来源：http://dali.zhoulong.xyz/Article/details/gt2yzcsohoe.html

Ruby: 42.to_s
来源：http://dali.cashguo.top/Article/details/gt2qmyrudys.html

C#:   42.ToString()
来源：http://dali.fzhhl.top/Article/details/gt2jhwhkcma.html

[A08] 取整与四舍五入
来源：http://dali.0kj1m.cn/Article/details/gt2wuuwppgq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gt2kkuwyozb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hfpthk.cn/Article/details/gt2mqmsccwt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gt2swrhelgw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcrtrvdx.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdavcqab.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gt2fojtjmhs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.aibaodan.cn/Article/details/gt2hjuooxim.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gt2vrazrsng.html

[A09] 绝对值与最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2owmibjaf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2gsgolyoy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2awtbqfzg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2vfwvsgcb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2pvozzhxk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2ggirkemq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmdesrdk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gaohongyu789.top/Article/details/gt2bstjzuxj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2xnmyvioe.html

[A10] 生成随机数
来源：http://dali.kuanghao11.cn/Article/details/gt2pktmvrlh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktliyzyl.html

PHP:  random_int(1, 100);
来源：http://dali.jqgfzy.top/Article/details/gt2uewuwmrb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.birdmap.top/Article/details/gt2flitpbaa.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hfpthk.cn/Article/details/gt2pkencrnx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxwkvpyo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yuanzhike.top/Article/details/gt2zzobxtsn.html

Ruby: rand(1..100)
来源：http://dali.hnqzz.top/Article/details/gt2rakznxst.html

C#:   new Random().Next(1, 101)
来源：http://dali.sweek.top/Article/details/gt2reyxbvit.html

[A11] 条件表达式（三元）
来源：http://dali.xylfe.cn/Article/details/gt2fjfaxpkx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ymlohnts.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gt2tezdbqev.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gt2kepkommv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gt2ucwxdwts.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gt2weqcnwmt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.aizwys.cn/Article/details/gt2gqfqfibf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gt2mgcsmvkr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iowjpnfs.html

[A12] 字符串插值 / 格式化
来源：http://dali.sysykeji.top/Article/details/gt2wfldhray.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.haohaochexian.top/Article/details/gt2olsfqwrw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xuanzx.com/Article/details/gt2pnhprnhp.html

JS:   `Hello, ${name}!`
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmgxsusp.html

TS:   `Hello, ${name}!`
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgbsswiu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinqigufen.top/Article/details/gt2ekkehuer.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxinkj.top/Article/details/gt2zkyjecbf.html

Ruby: "Hello, #{name}!"
来源：http://dali.hywenlv.cn/Article/details/gt2kpeyiqpv.html

C#:   $"Hello, {name}!"
来源：http://dali.yuanzhike.top/Article/details/gt2xkyepgai.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xziqi.cn/Article/details/gt2bqebyjuf.html

Py:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2iaxbvgwi.html

PHP:  "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gt2hmkpqpkz.html

JS:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2muwcobev.html

TS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2ypghwfrz.html

Java: "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2sompputh.html

Go:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gt2tgrtpntl.html

Ruby: "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gt2pjzyvimz.html

C#:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2qzzakzlj.html

[A14] 注释写法
来源：http://dali.daria6918.cn/Article/details/gt2btkarlsi.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhiwuduotai.top/Article/details/gt2keyqpjpu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfyylatq.html

JS:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gt2csegmqsp.html

TS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqyzuuvq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cdnleiting.top/Article/details/gt2nqxooklq.html

Go:   // 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gt2gbtkdyhv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgufenzy.top/Article/details/gt2qdyrenhg.html

C#:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gt2raphfqvd.html

[A15] 空值判断与默认值
来源：http://dali.hnqzz.top/Article/details/gt2mznprjtp.html

Py:   value = data or "默认值"
来源：http://dali.hfpthk.cn/Article/details/gt2flbfucwp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdubfcxu.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gt2wslpfijy.html

TS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gt2enhkounl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pquznkdf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmadwowy.html

Ruby: value = data || "默认值"
来源：http://dali.jyoumei.cn/Article/details/gt2bjeomasz.html

C#:   var value = data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gt2qdwbrzac.html

[A16] 真假值判断规则
来源：http://dali.meibo888.top/Article/details/gt2ksmifkda.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.chenzaomai.com/Article/details/gt2zsdqmltp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.vqdsnc.cn/Article/details/gt2auzbddhy.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjytjldp.html

TS:   if (!x) {}
来源：http://dali.xuanzx.com/Article/details/gt2ewxdulpb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hfpthk.cn/Article/details/gt2gfncpnbu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.pycfn.com/Article/details/gt2schqwznz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yvedp.cn/Article/details/gt2gbywoabo.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xuanzx.com/Article/details/gt2xbuxneqm.html

[A17] 位运算
来源：http://dali.sweek.top/Article/details/gt2ldvxwbnv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2nbpvukml.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yonumen.top/Article/details/gt2uvdmarjz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qazzkzmq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gt2wjoxrbcz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2hcbuonqj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gt2yqvtwixd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gt2rczmfjfq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2setewcqc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hammf.cn/Article/details/gt2lazipdgi.html

Py:   ord("A"); chr(65)
来源：http://dali.cqqwz.cn/Article/details/gt2sxadggwe.html

PHP:  ord("A"); chr(65)
来源：http://dali.shzxlz.cn/Article/details/gt2mrwnfybu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hammf.cn/Article/details/gt2kedxwkzk.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daxiang520.top/Article/details/gt2tlelidny.html

Java: (int) 'A'; (char) 65
来源：http://dali.cucudq.cn/Article/details/gt2oynpllkd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.wangdashe.top/Article/details/gt2ecvebgwm.html

Ruby: "A".ord; 65.chr
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwpbwnqm.html

C#:   (int)'A'; (char)65
来源：http://dali.yj202588.top/Article/details/gt2fqiqbrqv.html

[A19] 交换两个变量
来源：http://dali.hnqzz.top/Article/details/gt2fcsuasof.html

Py:   a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gt2nswbuwhq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.316326.xyz/Article/details/gt2yyouvhkz.html

JS:   [a, b] = [b, a];
来源：http://dali.pengpengdd.cyou/Article/details/gt2wysdoptj.html

TS:   [a, b] = [b, a];
来源：http://dali.xziqi.cn/Article/details/gt2evzebmzm.html

Java: int t = a; a = b; b = t;
来源：http://dali.tanke756.top/Article/details/gt2ofsjebea.html

Go:   a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgajrvuk.html

Ruby: a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gt2bncyymhi.html

C#:   (a, b) = (b, a);
来源：http://dali.xylfe.cn/Article/details/gt2qrlwefpl.html

[A20] 读取标准输入
来源：http://dali.gzhubu.top/Article/details/gt2xiesexkq.html

Py:   name = input("请输入：")
来源：http://dali.yuanzhike.top/Article/details/gt2lujfxmem.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.quarkkingdee.top/Article/details/gt2ciehijmh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yueranfly.top/Article/details/gt2qrkvimii.html

TS:   // Node.js：readline 模块
来源：http://dali.gogol.net.cn/Article/details/gt2jphuwzfi.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.nwbrower.top/Article/details/gt2rambiror.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhqpbfgk.html

Ruby: gets.chomp
来源：http://dali.cashguo.top/Article/details/gt2kygsxwjp.html

C#:   Console.ReadLine();
来源：http://dali.aizwys.cn/Article/details/gt2wlfzonhz.html

[A21] 保留指定小数位输出
来源：http://dali.xinyue.icu/Article/details/gt2zklbyqbz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hnqzz.top/Article/details/gt2pqnqgowp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gt2fyorhntg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2irylnlfh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gt2azmbjgks.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gt2zgnptcfl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gt2ffivagud.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gt2lqnldyan.html

C#:   3.14159.ToString("F2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkrkqsjp.html

[A22] 获取字符串长度
来源：http://dali.haohaochexian.top/Article/details/gt2fjgdulvh.html

Py:   len(s)
来源：http://dali.yj20258888.top/Article/details/gt2ktqceorg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cqqwz.cn/Article/details/gt2ghcejmlh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.aizwys.cn/Article/details/gt2uvpfevus.html

TS:   s.length
来源：http://dali.sxryk.cn/Article/details/gt2dmwmexfx.html

Java: s.length()
来源：http://dali.cheryme.top/Article/details/gt2ijbrwwom.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2nvyruhjn.html

Ruby: s.length
来源：http://dali.aizwys.cn/Article/details/gt2hgmngjri.html

C#:   s.Length
来源：http://dali.pycfn.com/Article/details/gt2eciemwus.html

[A23] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gt2dqjpnpdi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gzhubu.top/Article/details/gt2pyepgdmy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jlsjyb.cn/Article/details/gt2qmxkgczw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gt2prsxyehs.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuxming.cn/Article/details/gt2zubelqer.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gt2wzfveont.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2fvwmftjd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yvedp.cn/Article/details/gt2pyaysctw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shzxlz.cn/Article/details/gt2btpdsrrc.html

[A24] 去除首尾空白
来源：http://dali.guannengcc.top/Article/details/gt2pexcoezn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gogol.net.cn/Article/details/gt2akxtgmqn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ydzc1.top/Article/details/gt2hgtffouw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zgnnhhqx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tianlin.xyz/Article/details/gt2firckbvs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.dashuyun.cn/Article/details/gt2vklfvikm.html

Go:   strings.TrimSpace(s)
来源：http://dali.cheryme.top/Article/details/gt2byuikcez.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nwbrower.top/Article/details/gt2oryvlewz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hysaishi.cn/Article/details/gt2nsgmrzep.html

[A25] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2kmsocgzy.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daria6918.cn/Article/details/gt2imgguidb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigfzy.top/Article/details/gt2dmgysrff.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2juyrrwnl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gt2cksguijr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tanke756.top/Article/details/gt2rwtveykp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gt2bjvmkmqi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.guowangkeji.top/Article/details/gt2zuopseym.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gt2coswpzhs.html

[A26] 类型转换总览
来源：http://dali.feifeiyinyue.top/Article/details/gt2obplmdag.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fengsongda.top/Article/details/gt2gbfnnpjm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shuidangran.top/Article/details/gt2roggkyml.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jianghu66.top/Article/details/gt2doqazxdt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xylfe.cn/Article/details/gt2agelznny.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gt2cwdhrxxh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yuxming.cn/Article/details/gt2jynjydyw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.redwolf501.top/Article/details/gt2ggxlxmzb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gt2pimdfast.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2pnpjymud.html

B. 流程控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgthnpsb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2pmttnpdt.html

[B01] 条件判断 if / else
来源：http://dali.316326.xyz/Article/details/gt2qlegnxfc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yueranfly.top/Article/details/gt2kwvsjwbg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jianghu66.top/Article/details/gt2rpkiunun.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gt2iwlsqwpp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gt2lbixlqda.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gt2qrlpepdx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ehwqpu.com/Article/details/gt2fjkntqgr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hongshengwenyu.top/Article/details/gt2syfnoiwu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gt2gdnefcxv.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258.top/Article/details/gt2gstmievp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shuidangran.top/Article/details/gt2nbbmkurp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vebgfham.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gt2jsncjoww.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gt2izdownaj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gt2dreczrie.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.haohaochexian.top/Article/details/gt2xssqdtkb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zdqjudy.top/Article/details/gt2pgwawbjk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gt2uboiqxwn.html

[B03] switch / match / case
来源：http://dali.yanxiufei.cn/Article/details/gt2mvuxatqi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhixingplan.top/Article/details/gt2hiwmdrnb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gt2ymwdovwp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gt2ttjuvhff.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2vmllhhzr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gt2pacolpdt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.iojbl.cn/Article/details/gt2eeqhaqql.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhoulong.xyz/Article/details/gt2wvmclqlc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.iojbl.cn/Article/details/gt2hpavendh.html

[B04] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gt2ooggquwq.html

Py:   for i in range(10): print(i)
来源：http://dali.zhixingplan.top/Article/details/gt2robhzlbd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ppjwa.cn/Article/details/gt2plvmfzrt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangdashe.top/Article/details/gt2szcyjcxg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.redwolf501.top/Article/details/gt2hvlxauto.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinqigufen.top/Article/details/gt2ofqtdntf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uweyqsrc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cucudq.cn/Article/details/gt2ybtlrndp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fengsongda.top/Article/details/gt2euqtbkrw.html

[B05] 遍历数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gt2atfotijl.html

Py:   for item in arr: print(item)
来源：http://dali.hnxiangtu.top/Article/details/gt2retrgawg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtkfkibv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gt2gkglczgs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ekiyhanh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2xftjrlic.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gt2rwhyezeb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cashguo.top/Article/details/gt2zgbhwlfb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2ihkyuoyc.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gt2zeiyzkck.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gt2tbthefwt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pycfn.com/Article/details/gt2lfqrvted.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gt2ccwynhds.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gt2sfdllsxr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uigcwjqv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbableig.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenlongwang.top/Article/details/gt2tifbthva.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tanke756.top/Article/details/gt2ovpqwxas.html

[B07] while 循环
来源：http://dali.vqdsnc.cn/Article/details/gt2owretumo.html

Py:   while i < 10: i += 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbcovmzp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccwmsmgc.html

JS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2jfiiumuz.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gt2gnogzpja.html

Java: while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gt2djbmlruk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.iojbl.cn/Article/details/gt2xcoplsoc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.andypj.xyz/Article/details/gt2jjgdxnuq.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2zjmoqnmy.html

[B08] do-while（至少执行一次）
来源：http://dali.nwbrower.top/Article/details/gt2xtxjkffx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jlsjyb.cn/Article/details/gt2mehnuddf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2viwhkavk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2wyymkfdu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2helhjjsn.html

Java: do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2rgfohnuq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gt2pdzlntjp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gt2xrfuuqfw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2buykytok.html

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gt2xdpztbci.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.vqdsnc.cn/Article/details/gt2kjjwfhmu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2pteoznkv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2huwwtpsm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2fsmgwbbd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2ulrezbpg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ppjwa.cn/Article/details/gt2fnnrxrjf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daxiang520.top/Article/details/gt2hwpvhmtu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gt2xwodkkrf.html

[B10] 遍历同时拿索引
来源：http://dali.sxryk.cn/Article/details/gt2sgguqcst.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.c1oappe.top/Article/details/gt2hxpsgbba.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gt2xeizniwi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gt2dqncsufr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gt2ulbepyke.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gt2yuhlrunb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ehwqpu.com/Article/details/gt2yygqcocg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yanxiufei.cn/Article/details/gt2ztugpblc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cheryme.top/Article/details/gt2rqxrusvz.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigufen.top/Article/details/gt2ybbmqnfv.html

Py:   list(range(0, 10, 2))
来源：http://dali.hfpthk.cn/Article/details/gt2kzovbdmf.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnbtsxqz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2osxhryna.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2qhxnwpoc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgftqeyf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gt2jkufxlcg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gt2hhwtqlzb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yueranfly.top/Article/details/gt2xcsjlfxi.html

[B12] 跳出多层循环
来源：http://dali.chenlongwang.top/Article/details/gt2tsosbuej.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gt2cpqxzqud.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcacvbgs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gt2qjzxrdmj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2snixnwlg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2vuiqhalk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuxming.cn/Article/details/gt2inlxbfdy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gt2fxzsiyzb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gt2enrdmmre.html

[B13] 判断是否为数字
来源：http://dali.zhengqikj.top/Article/details/gt2fncfbrwo.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gt2gyogabqp.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gt2dhxkezwd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gt2auqklqsb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gt2alagbrqf.html

Java: x instanceof Number
来源：http://dali.feifeiyinyue.top/Article/details/gt2frnkyzud.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuetiantiany.cn/Article/details/gt2arqfjrzx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gt2potasxwk.html


<!-- 参考信息 -->