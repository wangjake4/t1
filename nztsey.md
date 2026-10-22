代发 wailian999

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoqplib.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrygeat.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2iefykhiq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pefiprtv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pygrmvzy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqokdagr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvezzaq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2opwqcpzm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrozkbbq.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxulrjv.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2coapzhzj.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yalbavsw.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2irzysynm.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwowxfb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2momgdoto.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhmrkmy.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2pewtsess.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bztcrlbn.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2isejdaln.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2anuplrsj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfjexub.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyrercc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvwbrzy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2idsmmlpf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2znnogrvf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2mimrlinn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqgajzo.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2weuvznor.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgpdgsf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqenvbu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoqjlmc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qepcaplt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyfvrlc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2vycjemfy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxyjcde.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2plzssqiu.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlkbuxy.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtaxrac.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsrldmw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcqrktd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpupkiu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jnydxbka.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2weqsfoil.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmwlaqa.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2pprrzhej.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtsmpxj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2twkmpfxp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hndsajcl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbqefvg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2imqivhih.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kisajctr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vysamsys.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuibiyh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwzudzl.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oizpzkde.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgbsowd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjkpkva.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzgkhtm.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2pacaptgd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrblcxd.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lupmbdvo.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnehgxr.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2utphyoaz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2idbuwtto.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmxmoed.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwfwkad.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecajcuhi.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2urmvgdlp.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayibvfdj.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtvxtum.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbuwapk.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbtktum.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nvremlfl.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2gvefiwjc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2necjkrqh.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnoosuc.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tfskpeat.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2lruukrud.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjlptte.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2prvomhtv.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ryylqaqt.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2prowigta.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxgjfvz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwjervp.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2pueugmuo.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2joitrbzb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjecqtan.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdjntax.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqumcfqj.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2emrezsoy.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwnajaj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qhumywgr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2sorxvzqc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qfawifyd.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfzjbua.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfxjmhj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuvwufp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zidjevhy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyjhkqo.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vznlhyty.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dobiefkr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnjiqxr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlaseag.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2txutolla.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qajeouzs.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvbzjlv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2afzwrrnb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyaertf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzgfxyb.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2banywzhd.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggudomry.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrdspwz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2viooeard.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqkeqzu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2xsossvcs.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2znbosjpu.html

C#:   (int)'A'; (char)65
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzrbcul.html

[A19] 交换两个变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdtouxn.html

Py:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgqikuc.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkxcyhp.html

JS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgnhbyf.html

TS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2uzskvhic.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjatkzf.html

Go:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2hmakcthf.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2pkresunp.html

C#:   (a, b) = (b, a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wphyqtbz.html

[A20] 读取标准输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wxioymor.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gt2tncpzahx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gt2ineeanzf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhijiandao.cn/Article/details/gt2zjelbdrc.html

TS:   // Node.js：readline 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnrdnkx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfxvtbm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrzgkkd.html

Ruby: gets.chomp
来源：http://dali.zhijiandao.cn/Article/details/gt2nhorhsep.html

C#:   Console.ReadLine();
来源：http://dali.zhijiandao.cn/Article/details/gt2ffetbgup.html

[A21] 保留指定小数位输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxylovq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgkbgzy.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzwbjhn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2curoezks.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkczfrjy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2szgxcola.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2llxarinq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlncyicc.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdohxwl.html

[A22] 获取字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qpddhyho.html

Py:   len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnixfvj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhijiandao.cn/Article/details/gt2tiarkodo.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhijiandao.cn/Article/details/gt2imndldto.html

TS:   s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fazuwuui.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rheaynpu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiinkkg.html

Ruby: s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wlirgigu.html

C#:   s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2laxynrqf.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wntifyjo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2vygqvwzf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2njtctrkn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfohgnq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvkrxci.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtetpus.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdigtuwu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlfypko.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvyufhr.html

[A24] 去除首尾空白
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvguzcu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwmzpmh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2smevplbx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rthvyhfe.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xllyadla.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkwtssu.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xefqjpqo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhijiandao.cn/Article/details/gt2oclwefkg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2duiypgnk.html

[A25] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2clsmjzpn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhijiandao.cn/Article/details/gt2ystdnehy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdakurtf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mppgsxhf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2houbjsqf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2annnclhx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqitvmb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhijiandao.cn/Article/details/gt2necwbfpg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmulpsja.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrsxwbz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhijiandao.cn/Article/details/gt2leqzdcpc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhijiandao.cn/Article/details/gt2eufeatsl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gt2sohrzyqb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhijiandao.cn/Article/details/gt2guvpbich.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrzmvvy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jehnmmlm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2geijnzfo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecimphqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2beqjbeil.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qczyldps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtynroc.html

[B01] 条件判断 if / else
来源：http://dali.zhijiandao.cn/Article/details/gt2exewjamn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2exqccixa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arpnlkur.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhimzjd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2yostdbby.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2clkzyiix.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjtimcr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlubsglj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfpafjw.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gt2icwjlikt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxttsgxy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrbwizn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2cczmvpqm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2xhymqizg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2kbanicpi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlknckci.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhcctmy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzigdbis.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gt2nkthiadi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvktmpd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvzcudq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrnhbrs.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aodliceo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeazjmi.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrdflmx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrlkjne.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2oozbdmuj.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qutvxnla.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzsgnmx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otrufpzp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnifivr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prjiykmz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uykveyux.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gt2icokxngb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkaxmod.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2szjemahn.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2otrhvglf.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gt2cndqdkvr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hennbqjc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yerihzlt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvusptea.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhekajnq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qapsrjgf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2caffrlxa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmubanm.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiqomiy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2smayvrnp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhjtizv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlrcyff.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oznaothz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpotgkny.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjanwtm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdcwrle.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akbgtrsd.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpjqnqb.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkfjhwm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkknvnj.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slmfddnp.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhxrdup.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqponkt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoxudje.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2byvisybf.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvodrnpi.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxztrqp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2twxgjvor.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkjhlqh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2dthswzql.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2babygwaj.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzsdxnl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrumojy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlypxkv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2cassbnlo.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdxeugh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2forpyhsd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqglxytc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muftpxpk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsqrfqz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpygeff.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxycgobm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecthpwjz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaevpoq.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2erndpvce.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxamdouq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfemygzj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrduhwz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2nftbitdj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkhaxrm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdxjhuf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iauwnxao.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnfimof.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2qymvmyra.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2elpqsltz.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfxpzee.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2myhwbhsg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvwoawk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiwzmvs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdjioih.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2tizmtixc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtzmyuv.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ybigjwtb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvlenri.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoptqqf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uymmixft.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntczoxdf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiduuook.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oelbiqbk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzniibd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcrjiia.html


<!-- 参考信息 -->