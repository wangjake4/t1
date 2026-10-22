代发 wailian999

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wmealkqe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2blquzsco.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2zuthbqtx.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2snomvaaj.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2aywdixfe.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2faymmlch.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfkfhru.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmbblnb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsnhpjj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrajcweh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcbykcy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnojbau.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oexalass.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfosatbj.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2swwppsje.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knorfdfk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkxrvzp.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2zwigglns.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjhokuw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vadnxpio.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcllslop.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2metomtsk.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyawavtu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjxvruh.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqejbhty.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrdmgoj.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifprkxgm.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzqilsp.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpfmfiv.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2efwmrxan.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbmpvra.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyzdjlq.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kuenaiqe.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzwjyua.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwsgewb.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2erwqmeao.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvzuvlz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2twczsgoj.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2aaecvhdh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2gpopfgss.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2skyujwwk.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgicixl.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvynhkkk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2giubuksk.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2rohawpfl.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoqhema.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlqgmuj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqglytgz.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2djgjtuno.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2becahruz.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2uztcxyma.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2brhydeok.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbssoye.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2oabgxmcn.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syzzvlmt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mremtlyf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjwzqjt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jyshevmb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfcqpbo.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2okcelcrd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2anrfhbtr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdyxmxj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hufgclhk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qewlmugj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uxycqwge.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wectvnxm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bllcrkok.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2stjwoqcj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcspjnk.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2piookkbb.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2sivkhsum.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2mabeetgi.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2ascpahhe.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2okrtpweo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2liyjvzsh.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwsdysl.html

C#:   (int)'A'; (char)65
来源：http://dali.zhijiandao.cn/Article/details/gt2egcyspys.html

[A19] 交换两个变量
来源：http://dali.zhijiandao.cn/Article/details/gt2huynjzhe.html

Py:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2efwptynv.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhvqmqt.html

JS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeqxayw.html

TS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxjhrdo.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gt2egzyvrar.html

Go:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhrqxyu.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmusccc.html

C#:   (a, b) = (b, a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dntfyxeh.html

[A20] 读取标准输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnujtko.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gt2junhgzek.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gt2aomantcu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzpmtgw.html

TS:   // Node.js：readline 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhfoxnr.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmaexox.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvibjitu.html

Ruby: gets.chomp
来源：http://dali.zhijiandao.cn/Article/details/gt2idlhbumo.html

C#:   Console.ReadLine();
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvfnizl.html

[A21] 保留指定小数位输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcjmkym.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iitqjyhb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2copegzrv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzusaggh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nszzhesk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbybzuh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpogoggh.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekljfehh.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjxdkyp.html

[A22] 获取字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pbudaycq.html

Py:   len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2feotbyqu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhijiandao.cn/Article/details/gt2mylenrte.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhijiandao.cn/Article/details/gt2shbvkylu.html

TS:   s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtpnnnm.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgezewyd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmwnyig.html

Ruby: s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpcfvwc.html

C#:   s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhrtdnl.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqczlkhf.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwibcknz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzpbhoa.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgutsno.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhujtrod.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaltgjy.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnnswqv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrdajbr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwpsppq.html

[A24] 去除首尾空白
来源：http://dali.zhijiandao.cn/Article/details/gt2tluwfbla.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwwvuwk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2szxgigmd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuupewjw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bernprpi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhmmrpd.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpkcdpu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhijiandao.cn/Article/details/gt2vusfizrr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpygtrbl.html

[A25] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcughgy.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhijiandao.cn/Article/details/gt2spcjmted.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjscnkcb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtgmscw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgaqfng.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzgyaom.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhmumhu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhijiandao.cn/Article/details/gt2cptyevnp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxipzjfc.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gt2csyximoa.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhijiandao.cn/Article/details/gt2urcwhept.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqfxdnb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvhebmc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhijiandao.cn/Article/details/gt2duunekkt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2aipgdfrk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjduqxyp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2oomyhxnb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhisdvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxakuvt.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cwolpnny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqodslx.html

[B01] 条件判断 if / else
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzemyox.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxxqrtp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjozazgj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2injmhdvw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ziczbhei.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2afnlydoi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmztggdu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vditubik.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2actdehcu.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gt2zdobxajn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gt2syffgxyf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raijzuit.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiapyhh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtbmyxr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2pujsleyb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zummftke.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmxtvzd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgemtek.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcjlzet.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gt2iombhgsq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhnkenm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvswvwm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrahxjg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxuqewn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwpfzmj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfhfbnx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lapjxvpl.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgoxodk.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrxhreu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxytxjcd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzmkhqi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkdlkci.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrjjajv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sljsmiop.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzucbtf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwypxgr.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbuemvp.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gt2epgkhroi.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfkvbqk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sertagjr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnhtrhy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djpcoofg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2earnmmal.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxavdqti.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhymlway.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qzauzeea.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsaukpl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjluzht.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvzmefb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeaxnda.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhozsmss.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxncaaey.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tenfifyy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxfzjti.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mempagjb.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2inwgatti.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mizaxbgp.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrfxvbj.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzyqhav.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yinzgbju.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qriwvvui.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrikzosy.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaoryog.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeukbwi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2npbmhzeq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2becsvunc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2rleiufjy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2xggzeueg.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqfbkbz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkclvwhf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qafajseb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuubrjjz.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgagdid.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gykarttl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymucgwge.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqqsarp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eluvqayy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhaepcx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vllitrac.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sheqrord.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcolrphd.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2orqbjryh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqynonzn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpcxcbm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2nesjzshu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2hjunmiiz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmdhmgb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqrfckg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rljvalxx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjdyntn.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2hjamyasu.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxqlpzw.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2txmnwhjs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aitkiana.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdgmayg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmydmjy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiyctml.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjysfns.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eithkwql.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2njxkrdmk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2lduaqhyb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzdsxgl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnijegfl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2flhsohav.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltncoqat.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wairrcto.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2unhxxhtj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2gomnroxi.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxpgsnv.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2izfkbqdt.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2klfzqyhb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lftcteko.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xirwlmla.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyusetu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsbsdui.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2prngydbq.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpbdyqw.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmlmwhh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfvmerv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsdjnhh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvmynwr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwgrxqo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxhsfyv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqpqoue.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2acspcrvn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2udlqraxa.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2vjygbjua.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoqpgcz.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2qaizeaju.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqykxeg.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlexbuo.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzwffls.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnjnwxt.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvxxehm.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlpmajc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmawphr.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2yajvwsqg.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qskoieeq.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ritsusia.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2baxwgyfa.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2oldejdyk.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcdixbz.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2kqplczgv.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ireogxgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trblxyop.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrzxuua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyalbxab.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqpuibx.html


<!-- 参考信息 -->