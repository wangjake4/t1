代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtqwbsryps.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gteofvpmoi.html

[A12] 字符串插值 / 格式化
来源：http://dali.jyoumei.cn/Article/details/gtcmluralv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zycfv.cn/Article/details/gtlkmcmrld.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.chenlongwang.top/Article/details/gtjywlfyfr.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gtpnqmcumh.html

TS:   `Hello, ${name}!`
来源：http://dali.zhoulong.xyz/Article/details/gteuyqhbbt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.pengpengdd.cyou/Article/details/gtoortykll.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.guannengcc.top/Article/details/gthqtoobsq.html

Ruby: "Hello, #{name}!"
来源：http://dali.tianlin.xyz/Article/details/gtpfbsrvyb.html

C#:   $"Hello, {name}!"
来源：http://dali.aibaodan.cn/Article/details/gtotwnbyey.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.daxiang520.top/Article/details/gtqwhuewom.html

Py:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtvzdbprsy.html

PHP:  "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtszfdmzln.html

JS:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtmlmcjhpy.html

TS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtvhybfreo.html

Java: "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtvsztqowo.html

Go:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtnxwxvqhk.html

Ruby: "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtnejbpqbb.html

C#:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtlcgcwsxa.html

[A14] 注释写法
来源：http://dali.tianlin.xyz/Article/details/gtzounyify.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hongshengwenyu.top/Article/details/gttzujofzp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gtgwsnodzk.html

JS:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtjdzrufmo.html

TS:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtvvgbpevn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cucudq.cn/Article/details/gthmcsipfh.html

Go:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gtkoicojqv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yangfankeji.com/Article/details/gtqqsldazz.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhixingplan.top/Article/details/gtrxzfotuv.html

[A15] 空值判断与默认值
来源：http://dali.ydzc1.top/Article/details/gtudvthkqa.html

Py:   value = data or "默认值"
来源：http://dali.9152youxi.cn/Article/details/gtdrwyqnuo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gtoxenuxlb.html

JS:   const value = data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gtasjivoeb.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjpklxmy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jlsjyb.cn/Article/details/gtamduzlnp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.316326.xyz/Article/details/gtlvxidakg.html

Ruby: value = data || "默认值"
来源：http://dali.xuetiantiany.cn/Article/details/gtyulupnjr.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gtjdfsbnby.html

[A16] 真假值判断规则
来源：http://dali.hywenlv.cn/Article/details/gtkdxudkaa.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shuidangran.top/Article/details/gtsfvnkgwb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.316326.xyz/Article/details/gtfmwvxepp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hammf.cn/Article/details/gtjnbnsjny.html

TS:   if (!x) {}
来源：http://dali.tian-w.cn/Article/details/gtfdxemkjv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.tianlin.xyz/Article/details/gtizihqtzr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hysaishi.cn/Article/details/gtosdkkncd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.smart0.xyz/Article/details/gtqageobgv.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.fengsongda.top/Article/details/gtrrqjvlco.html

[A17] 位运算
来源：http://dali.sweek.top/Article/details/gtngcjtmez.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtaewddbxp.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.guannengcc.top/Article/details/gttrohfkuk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtvutyzuhq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpfmmuvi.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgagermjo.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtmemntmdk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtqcmozfkd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtuzqmlslg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhiwuduotai.top/Article/details/gtmszrgzxw.html

Py:   ord("A"); chr(65)
来源：http://dali.yuanzhike.top/Article/details/gtbrndiypd.html

PHP:  ord("A"); chr(65)
来源：http://dali.gogol.net.cn/Article/details/gtmiyfvpzm.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtxsjdhapc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yonumen.top/Article/details/gtsjmamlqm.html

Java: (int) 'A'; (char) 65
来源：http://dali.hnqzz.top/Article/details/gtugvqmryb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxinkj.top/Article/details/gtuhloraar.html

Ruby: "A".ord; 65.chr
来源：http://dali.xinyue.icu/Article/details/gtakrhinvj.html

C#:   (int)'A'; (char)65
来源：http://dali.zhongyouzk.top/Article/details/gtfenljfdl.html

[A19] 交换两个变量
来源：http://dali.feifeiyinyue.top/Article/details/gtrtprgcbh.html

Py:   a, b = b, a
来源：http://dali.0kj1m.cn/Article/details/gtxhdlplos.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.316326.xyz/Article/details/gtilmidjbf.html

JS:   [a, b] = [b, a];
来源：http://dali.iojbl.cn/Article/details/gtgiobsrsk.html

TS:   [a, b] = [b, a];
来源：http://dali.cucudq.cn/Article/details/gtulxvkckp.html

Java: int t = a; a = b; b = t;
来源：http://dali.wangdashe.top/Article/details/gtkfgyzgcq.html

Go:   a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gtuigmbkbp.html

Ruby: a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gtuprybptj.html

C#:   (a, b) = (b, a);
来源：http://dali.jinqigfzy.top/Article/details/gtzxvigslk.html

[A20] 读取标准输入
来源：http://dali.ppjwa.cn/Article/details/gtiicymlmw.html

Py:   name = input("请输入：")
来源：http://dali.yueranfly.top/Article/details/gtmtkfcovq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gzhubu.top/Article/details/gtqedrhktm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nanxuanxn.top/Article/details/gthxxdeqmt.html

TS:   // Node.js：readline 模块
来源：http://dali.svipenyu.cn/Article/details/gtkhwyqfja.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggvgxsrv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cheryme.top/Article/details/gttyvgeqxj.html

Ruby: gets.chomp
来源：http://dali.zhengqikj.top/Article/details/gtqfhxwuim.html

C#:   Console.ReadLine();
来源：http://dali.jqgfzy.top/Article/details/gtecguvify.html

[A21] 保留指定小数位输出
来源：http://dali.meibo888.top/Article/details/gtzvdsxphc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.havefunace.top/Article/details/gtkgmlsjsu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtqmdrzmhw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbudzreng.html

TS:   (3.14159).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtmrrwidax.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtqvifdgkv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtvmlneuqf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbrwxmiv.html

C#:   3.14159.ToString("F2")
来源：http://dali.birdmap.top/Article/details/gtfcmfifvb.html

[A22] 获取字符串长度
来源：http://dali.ydzc1.top/Article/details/gthmuanvcz.html

Py:   len(s)
来源：http://dali.sweek.top/Article/details/gtofavuldx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.smart0.xyz/Article/details/gtxkzrypkl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gaohongyu789.top/Article/details/gtdkwnepbx.html

TS:   s.length
来源：http://dali.zhixingplan.top/Article/details/gtnyneazzg.html

Java: s.length()
来源：http://dali.pycfn.com/Article/details/gtfbagjlhb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtptcndovy.html

Ruby: s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtvimsjhfz.html

C#:   s.Length
来源：http://dali.9152youxi.cn/Article/details/gthwyasjig.html

[A23] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtnjbxzwwv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hnqzz.top/Article/details/gteustxogx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hywenlv.cn/Article/details/gtaotkzykx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gtizoqevfp.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhdyavpo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gotoacloud.top/Article/details/gtstvcbccg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hammf.cn/Article/details/gtuptbwziu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gtqgtjitrz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.havefunace.top/Article/details/gtmgygowjd.html

[A24] 去除首尾空白
来源：http://dali.c1oappe.top/Article/details/gthxwyjixy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.nanxuanxn.top/Article/details/gtncdstanl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sxryk.cn/Article/details/gtjxnarntf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ydzc1.top/Article/details/gtlxaffneq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258888.top/Article/details/gtjanpavux.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yuxming.cn/Article/details/gtijkprcrd.html

Go:   strings.TrimSpace(s)
来源：http://dali.haohaochexian.top/Article/details/gtpdckuifk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhengqikj.top/Article/details/gtzintoliz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.pycfn.com/Article/details/gtfaamozpf.html

[A25] 字符串比较
来源：http://dali.meibo888.top/Article/details/gtmsinysyx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangdashe.top/Article/details/gtyuxfbweb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jianghu66.top/Article/details/gtvqxghomm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gtjilalppu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.bjfxy.top/Article/details/gtmfqmrwqj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jianghu66.top/Article/details/gtuqioatuf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yvedp.cn/Article/details/gteykyinfv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywmuzndx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqehpexl.html

[A26] 类型转换总览
来源：http://dali.zhiwuduotai.top/Article/details/gtsccgldqw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jiagoushi.top/Article/details/gtcdqtpgmf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yongpay.top/Article/details/gtnhmwbzwg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gtgkzeilio.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnqzz.top/Article/details/gtsqzijjac.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gogol.net.cn/Article/details/gtqmzeukur.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangdashe.top/Article/details/gtmhbhstnv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yongpay.top/Article/details/gtkecsvkmd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hysaishi.cn/Article/details/gtbiituitf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdyaysuwc.html

B. 流程控制
来源：http://dali.jinqigfzy.top/Article/details/gtjuyzsqax.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrbuumdxt.html

[B01] 条件判断 if / else
来源：http://dali.yonumen.top/Article/details/gtfpisguwu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jqgfzy.top/Article/details/gthwavwsis.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dashuyun.cn/Article/details/gthlsowybf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtpaezxtgq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtumuhiulg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtuczlbljv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.svipenyu.cn/Article/details/gtukucajzf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sysykeji.top/Article/details/gtldwoljqb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtskuilqzg.html

[B02] 多分支 else if / elif
来源：http://dali.yongpay.top/Article/details/gtjfmejleh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrveawqix.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fengsongda.top/Article/details/gthvowsffx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtcradgwjx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtimagmojj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtmphhvsop.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuanzx.com/Article/details/gtsjdnfhme.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yangfankeji.com/Article/details/gtimevwvmi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlobmqbua.html

[B03] switch / match / case
来源：http://dali.gzhubu.top/Article/details/gtbddtdqfr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangdashe.top/Article/details/gtvkqbhjqy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtlggupuev.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtuznhvvrb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtidihggak.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgodmfkcr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtvhegjmdh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sweek.top/Article/details/gtdmxsuvbp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gtcrwjottr.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtuewrjutn.html

Py:   for i in range(10): print(i)
来源：http://dali.fengsongda.top/Article/details/gtzrzvnugi.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daria6918.cn/Article/details/gtaqdbznjn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gthzpuyxrj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gtzpcbubgx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sweek.top/Article/details/gtlfrisopm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ydzc1.top/Article/details/gtkreudqch.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sxryk.cn/Article/details/gtamjujobl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cashguo.top/Article/details/gtoxjottgw.html

[B05] 遍历数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtsbrlpkxk.html

Py:   for item in arr: print(item)
来源：http://dali.jianghu66.top/Article/details/gtdwfrdtuz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.guowangkeji.top/Article/details/gttwrowfxw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtmdayonjt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gtcbxmngos.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yonumen.top/Article/details/gtsoewgdqr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xylfe.cn/Article/details/gtihnmvorp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuanzx.com/Article/details/gtjftlqquf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gtqcrghqwf.html

[B06] 遍历字典 / 对象
来源：http://dali.tianlin.xyz/Article/details/gtyewrckgv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhongyouzk.top/Article/details/gtwyaokmze.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yonumen.top/Article/details/gteuxwdmri.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gtveeztqqk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gtqebfdljn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jlsjyb.cn/Article/details/gtecvqtjbq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ppjwa.cn/Article/details/gtinhydidc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gtelxjrtsj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfqprdzk.html

[B07] while 循环
来源：http://dali.shzxlz.cn/Article/details/gtlcubocsc.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gtohsqdjfe.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtydwutpvu.html

JS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtgdlhklnm.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtdxhwqpcz.html

Java: while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtirgvocoh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.mhx1999.top/Article/details/gtaftjthpt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daxiang520.top/Article/details/gtxdapmyje.html

C#:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtibspcgja.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gtwedrxnnq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.redwolf501.top/Article/details/gtfhblmzkd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shuidangran.top/Article/details/gtgihuxljy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtmxwmwkgc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gttlxwjjsy.html

Java: do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtxnqlnabz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtyjdlfvak.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuafzfwd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtyytojwxy.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gtmfbgfiyq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuxming.cn/Article/details/gtzntdrgho.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtzvhspdxp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtjqfrovwk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwktzogey.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtbyoipbgs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gtavidnxqg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hongshengwenyu.top/Article/details/gtspvlwgbh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtqzpdkxdz.html

[B10] 遍历同时拿索引
来源：http://dali.feifeiyinyue.top/Article/details/gtbanguyhw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gtlvazvtfz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.mhx1999.top/Article/details/gtmltrlnuy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtocfbbuse.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtrvvcxzta.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sufxvd.cn/Article/details/gtpzjejeuy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigufen.top/Article/details/gtjnyzesrm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gtpoyciido.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daxiang520.top/Article/details/gtziwftzxa.html

[B11] 生成数字序列 / 区间
来源：http://dali.haohaochexian.top/Article/details/gtfdhpckzt.html

Py:   list(range(0, 10, 2))
来源：http://dali.andypj.xyz/Article/details/gtpodxvnmo.html

PHP:  range(0, 10, 2);
来源：http://dali.jyoumei.cn/Article/details/gtuulpjpde.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gtflpogwjy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsfuatea.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tianlin.xyz/Article/details/gtscwecddl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gtgsxwhqff.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tianlin.xyz/Article/details/gtrlomtnww.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtgzrrqjnk.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gtqzvjbrjn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xinyue.icu/Article/details/gtcbncwuvp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gtzgkbujto.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtfnysklsy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtnmcbefrs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtawgvrqcq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cashguo.top/Article/details/gtdsylwpry.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shuidangran.top/Article/details/gtfmubuwxw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtvivdqbll.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gtivazbvjl.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gtkikncdew.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtyoqwzcsk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstybnjqx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gtzcpmzrrt.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gtfwqqelnn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gtbfbiualj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gtsqctwdde.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqtfyala.html

[B14] 判断值是否在集合内
来源：http://dali.jqgufenzy.top/Article/details/gtndfqsmrq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.redwolf501.top/Article/details/gtyxuknvii.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gtkgyhvdqc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtaliryagv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtvzaauwvj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtdtffaplu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yangfankeji.com/Article/details/gtczmftulj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtatuzkclv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtqxsfjnub.html

[B15] 布尔运算与取反
来源：http://dali.nanxuanxn.top/Article/details/gtecmfyjnf.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gthcsxphqn.html

PHP:  $a && $b || !$c
来源：http://dali.pengpengdd.cyou/Article/details/gtjzqwlgcn.html

JS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtmccukojw.html

TS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtlwwxjymc.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtpeucbtok.html

Go:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtvogzqqiv.html

Ruby: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrfuhdeu.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gthprtlzbi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aibaodan.cn/Article/details/gtgbnhswzq.html

Py:   if not data: return
来源：http://dali.xziqi.cn/Article/details/gtkkwkvukg.html

PHP:  if (!$data) { return; }
来源：http://dali.smart0.xyz/Article/details/gtyivfpxat.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gthzxlxhik.html

TS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gteuammicy.html

Java: if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtbprhuocb.html

Go:   if data == nil { return }
来源：http://dali.sysykeji.top/Article/details/gtmkaggodf.html

Ruby: return if data.nil?
来源：http://dali.cucudq.cn/Article/details/gtjbspadaw.html

C#:   if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtfaesepgm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwwkaqmii.html

C. 函数与作用域
来源：http://dali.sysykeji.top/Article/details/gtpazfmigu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxcwuldor.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gttnpsseig.html

Py:   def add(a, b): return a + b
来源：http://dali.xziqi.cn/Article/details/gtvpkeeean.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtrklapkfe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtjdiqoolz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtkocbtglu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gthdvifibm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gtkwrcohre.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gtlhbeidbt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtwpwsdzqt.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtmwashare.html

Py:   def greet(name="World"): return name
来源：http://dali.zhoulong.xyz/Article/details/gtzpufttnw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtexlcubiv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtzctkigul.html


<!-- 参考信息 -->