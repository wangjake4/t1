代发 wailian999

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kufqazbi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2idnevoge.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2whmifzib.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmoskij.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dxislgmt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxxmiee.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsyxokw.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqtndiq.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpldkxdm.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzqdngr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wznyexkc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tybxfzcs.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkicvhqk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2edpmxsft.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqdbiey.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwufqti.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkbdlsn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2titvpcsm.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjleqvv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyvigxk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzcbtad.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2qvycwtgm.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaadsfd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2srtizzpf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzkprdj.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2npikzhun.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhzlshz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2zymjwycu.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rprbeloh.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvesajx.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzufgwdj.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbihkin.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwdbewr.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkjgmxr.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cssmsnhs.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxhtgkr.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fczzzzda.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2afirgdtj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2acrdojut.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyrwcas.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtrqdvq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bggnablu.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dayzimxc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2zofiqhgg.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhxpmec.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xtntogfs.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvuyycl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkpeqkq.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2yteumkxm.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2psonsore.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2buaplehk.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryctsdey.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbubhru.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqommmd.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmrydeg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xzccmswl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2appdtuit.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdcxivk.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdjjaba.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyoxsja.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkmpuyp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2aupdwsub.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbibxri.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjboyrc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2analdfuq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2usxequhb.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nxanlgcc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbqxhyv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzphtjg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxinrke.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjcepup.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhsopre.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2igezubew.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2btkwfjex.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwladovh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2rufvqtci.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpwfaau.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2wximnhwc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2onspjrjb.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqtsebu.html

C#:   (int)'A'; (char)65
来源：http://dali.zhijiandao.cn/Article/details/gt2sgizavtm.html

[A19] 交换两个变量
来源：http://dali.zhijiandao.cn/Article/details/gt2exhzeieh.html

Py:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzcprfx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhijiandao.cn/Article/details/gt2lzufcptv.html

JS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2obcsovmb.html

TS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpfgthc.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gt2lunwfequ.html

Go:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2uubatqft.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2brdbcsvt.html

C#:   (a, b) = (b, a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqclplqq.html

[A20] 读取标准输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjkobir.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gt2kguytxtj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtckvoj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhijiandao.cn/Article/details/gt2ircpcveq.html

TS:   // Node.js：readline 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xczwaxpn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhijiandao.cn/Article/details/gt2focjwqac.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhijiandao.cn/Article/details/gt2srhwfbsn.html

Ruby: gets.chomp
来源：http://dali.zhijiandao.cn/Article/details/gt2uduscwqf.html

C#:   Console.ReadLine();
来源：http://dali.zhijiandao.cn/Article/details/gt2qaapbagz.html

[A21] 保留指定小数位输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sytnalon.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhijiandao.cn/Article/details/gt2myzsrwsz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtpoldc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2skhztdno.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qojxfcxo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2xecapdcu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2etwsxzcv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbuszfd.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvxgtvh.html

[A22] 获取字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zjepmkrh.html

Py:   len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpujycmx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhijiandao.cn/Article/details/gt2luhmqbud.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhijiandao.cn/Article/details/gt2czkjmasd.html

TS:   s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkhxcnm.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzcfssk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2amugterd.html

Ruby: s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dehtlsue.html

C#:   s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hqghewjm.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zuapcgjp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2yktwkeza.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjsnhrt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjqctrq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfywnkzn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipempgah.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcayhqo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2vabvmemr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdouqcz.html

[A24] 去除首尾空白
来源：http://dali.zhijiandao.cn/Article/details/gt2jkveznad.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsupidp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfwqhvv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wppckaer.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmvlogd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gt2utogasko.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2khhylvbu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhijiandao.cn/Article/details/gt2mrivngln.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2owhqjmmw.html

[A25] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dscesemr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhijiandao.cn/Article/details/gt2emynilup.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmjojuw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bantwyxt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlqpbqh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhraorfd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xokghwbp.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxblyvz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmlqscd.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gt2qoeslaji.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhijiandao.cn/Article/details/gt2syhpclbe.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxmpsgi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrwohut.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjsvppi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwysgih.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tyersive.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vefooxdq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2eohvkeuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hebhxwls.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gt2oaladflj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghihzkbs.html

[B01] 条件判断 if / else
来源：http://dali.zhijiandao.cn/Article/details/gt2eopmanse.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwkveai.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awlizwpc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeemdkv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2eerzeisu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuvqqft.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdinqkea.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiikbkqs.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqcevsp.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzjgdsc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsyakww.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmlykpj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcybwfa.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjraduw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkwygio.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpytode.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlncnzi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2dywgbagb.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gt2accemayn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gt2oifdfmhn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apbubiuf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtnzxhe.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqteglqr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoexwfcl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2elqflogj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gt2mszwjkno.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqaaenp.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2trevsifr.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfroxhat.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyinomel.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odazcxll.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnkhyfl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjmzbxa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gt2blokhcdj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnelbsj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2huclyopr.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2onopqtru.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhwkvmn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjojzsr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzjdvmh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkjilev.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fatpskky.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uerpmgyr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2evmnvqok.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obpzicsc.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnkwttc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnwtibk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxmtihu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nriniygi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2duehrcsd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pygyahht.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oesoygiy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqnmsvx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wswncdes.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbiklmu.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcsbmyv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tinfsikw.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apivxyxt.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alyestzu.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeowgtwd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fnldtgok.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvjffrd.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iogbcijg.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwbigdb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlkjllc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlxqajq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2eolffusg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2wymftkos.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtidkrfp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsvjtss.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcfpwfo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqhqjei.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdkbegg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzmiapk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewraxtpa.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhkaokd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiualbu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlklskbh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkcgohm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sniumpik.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyegonwy.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ajahrjjl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2dydgiekd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fukklmef.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2zvozzeob.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2zchqchtv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgtpheg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwbiuuc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdstava.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzxlvck.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2khjhrgqo.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjohrcnw.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrrxitt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbxjgqk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdobswju.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtqucwv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2jssufzxg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmjxcty.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwxaqzc.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2irzykujx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2jekboakd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuszypm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfpstwc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmyauez.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfknmmu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etksdymr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kifevhib.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2nocbabrr.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lecohsgf.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2pokhhjrd.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2snenvuwl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sihctydw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzgsgau.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2atvrdmjz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2stthcffa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeralll.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2snbtpzpb.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrbxzmn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2snmxgpah.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrxxgnn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zojmrgqy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbqznkj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gepesbvu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgpwacp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wasjhixm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjszfjhe.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2uodxwviz.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbhtaof.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2gdptpbkg.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqaydji.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbcebka.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lctqutqn.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iplsjhze.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaxkisq.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcgjbjl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2adtfchqg.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2aizmtgyt.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qblarale.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuptqww.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2trxhuhqm.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzchakct.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcentim.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2slyeshla.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlxwpzg.html


<!-- 参考信息 -->