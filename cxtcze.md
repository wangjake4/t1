代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jqgfzy.top/Article/details/gtedpgaumo.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclcewmow.html

C#:   $"Hello, {name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gtytblplrs.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.0kj1m.cn/Article/details/gtprxzhvcb.html

Py:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaavgdkoj.html

PHP:  "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtycczybga.html

JS:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtnxexpytq.html

TS:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtwlsmecmt.html

Java: "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtvnqggiez.html

Go:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmsfkbto.html

Ruby: "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtfjwccngv.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtgdsdsdxf.html

[A14] 注释写法
来源：http://dali.0kj1m.cn/Article/details/gtdtpxzent.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cqqwz.cn/Article/details/gtxzxluetc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gteawpzwjt.html

JS:   // 单行；/* 多行 */
来源：http://dali.quarkkingdee.top/Article/details/gtnpydfmwo.html

TS:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gtfqvfquly.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.fengsongda.top/Article/details/gtpyontgzt.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gttsxqqtqx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shzxlz.cn/Article/details/gtrksnhtdi.html

C#:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtaexpigzg.html

[A15] 空值判断与默认值
来源：http://dali.hywenlv.cn/Article/details/gtetlnhbrs.html

Py:   value = data or "默认值"
来源：http://dali.jqgfzy.top/Article/details/gtdubwecma.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gtqiiynwdv.html

JS:   const value = data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gtbcvrpsdi.html

TS:   const value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gtcqhpdwtr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xuanzx.com/Article/details/gtjssqtcjt.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.svipenyu.cn/Article/details/gtnbyjltdv.html

Ruby: value = data || "默认值"
来源：http://dali.cdnleiting.top/Article/details/gtzdthewri.html

C#:   var value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gtbdnnqrcp.html

[A16] 真假值判断规则
来源：http://dali.cdnleiting.top/Article/details/gtyplnhmlu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtozlgiror.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhongyouzk.top/Article/details/gtrrevcbgv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jqgfzy.top/Article/details/gtqwxqvctg.html

TS:   if (!x) {}
来源：http://dali.nanxuanxn.top/Article/details/gtlngaaasz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.birdmap.top/Article/details/gtcmwlunzi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sxryk.cn/Article/details/gtdcfblrqt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinqigufen.top/Article/details/gtyempajlf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.dashuyun.cn/Article/details/gtbyuffcsu.html

[A17] 位运算
来源：http://dali.chenlongwang.top/Article/details/gtbuudircq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtlcieazjz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zdqjudy.top/Article/details/gttqvarogg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtjblwwcha.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtjzyrodlz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtwetqoiwd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtigbzoauj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtwpxijizy.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gthsesumne.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ivvv.top/Article/details/gttuptrqsw.html

Py:   ord("A"); chr(65)
来源：http://dali.9152youxi.cn/Article/details/gtxoukjkww.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenjidiqi.icu/Article/details/gtosgkjoyx.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtuvopcfut.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fengsongda.top/Article/details/gtetmgnsom.html

Java: (int) 'A'; (char) 65
来源：http://dali.gaohongyu789.top/Article/details/gtcfetclxg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.feifeiyinyue.top/Article/details/gtzxqsdase.html

Ruby: "A".ord; 65.chr
来源：http://dali.zycfv.cn/Article/details/gtsmojofnq.html

C#:   (int)'A'; (char)65
来源：http://dali.jlsjyb.cn/Article/details/gtetoeerah.html

[A19] 交换两个变量
来源：http://dali.ydzc1.top/Article/details/gtncctxdhk.html

Py:   a, b = b, a
来源：http://dali.pengpengdd.cyou/Article/details/gtftzqvgtv.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hywenlv.cn/Article/details/gtujkufixw.html

JS:   [a, b] = [b, a];
来源：http://dali.yanxiufei.cn/Article/details/gtegycvgli.html

TS:   [a, b] = [b, a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtkgbbvx.html

Java: int t = a; a = b; b = t;
来源：http://dali.aizwys.cn/Article/details/gttxqwojqq.html

Go:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtgbytjnju.html

Ruby: a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gtzvvoyubb.html

C#:   (a, b) = (b, a);
来源：http://dali.yj20258.top/Article/details/gtdkjlgdgi.html

[A20] 读取标准输入
来源：http://dali.jyoumei.cn/Article/details/gtfwnhjbpm.html

Py:   name = input("请输入：")
来源：http://dali.zdqjudy.top/Article/details/gtenxisywl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.kuanghao11.cn/Article/details/gtxqtqwhpx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yanxiufei.cn/Article/details/gtvzcbpgtf.html

TS:   // Node.js：readline 模块
来源：http://dali.cucudq.cn/Article/details/gtviepuwpf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhiwuduotai.top/Article/details/gtmkttltgr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jqgufenzy.top/Article/details/gtqwqxtzje.html

Ruby: gets.chomp
来源：http://dali.ehwqpu.com/Article/details/gtyhrxdcwp.html

C#:   Console.ReadLine();
来源：http://dali.yuanzhike.top/Article/details/gtesltbheh.html

[A21] 保留指定小数位输出
来源：http://dali.redwolf501.top/Article/details/gtyhedzpdt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tianlin.xyz/Article/details/gturgenkbp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gtsafjsscs.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtctuqbwjw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtpnioystt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtfujpxhxx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gtljkjvqok.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gtbhpkvwjf.html

C#:   3.14159.ToString("F2")
来源：http://dali.ivvv.top/Article/details/gtpjlddyid.html

[A22] 获取字符串长度
来源：http://dali.xylfe.cn/Article/details/gteevxcldn.html

Py:   len(s)
来源：http://dali.cqqwz.cn/Article/details/gtfilnnoos.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hywenlv.cn/Article/details/gtuwrcnptr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gotoacloud.top/Article/details/gtkksqrzou.html

TS:   s.length
来源：http://dali.svipenyu.cn/Article/details/gtnudzdfnn.html

Java: s.length()
来源：http://dali.cdnleiting.top/Article/details/gtbluepbzm.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jiagoushi.top/Article/details/gtrqddyian.html

Ruby: s.length
来源：http://dali.yueranfly.top/Article/details/gtrcadaztk.html

C#:   s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtwelyasdf.html

[A23] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gttdectfxt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtpctrejyf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cdnleiting.top/Article/details/gtovmntwva.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtfgtwsthg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtkebixcka.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.nwbrower.top/Article/details/gtmlzuieye.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvunjdddx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtbmrrrdcv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yanxiufei.cn/Article/details/gtdtpiiyhk.html

[A24] 去除首尾空白
来源：http://dali.hnxiangtu.top/Article/details/gtsclxbryn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jlsjyb.cn/Article/details/gtdsyxxoug.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guannengcc.top/Article/details/gtnhleeknz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gtskugiqen.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtfabavqjm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.meibo888.top/Article/details/gtlspkamkq.html

Go:   strings.TrimSpace(s)
来源：http://dali.yongpay.top/Article/details/gtesejrske.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shzxlz.cn/Article/details/gtxkobujkl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.redwolf501.top/Article/details/gtypipbeqg.html

[A25] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtficubheu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shzxlz.cn/Article/details/gtttllxthc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gaohongyu789.top/Article/details/gtlletbxdc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pycfn.com/Article/details/gttqbwywhh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtcqucjuxz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.aibaodan.cn/Article/details/gtqarujyng.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gtnxxctazt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuanzx.com/Article/details/gtevkueyxl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gtwpdqgjys.html

[A26] 类型转换总览
来源：http://dali.ehwqpu.com/Article/details/gtsdjwslxo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyothlrz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.meibo888.top/Article/details/gtyeasrzzz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj20258888.top/Article/details/gtizvlnncy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhiwuduotai.top/Article/details/gtxfzkylxq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gtfvxnejgs.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sufxvd.cn/Article/details/gtsoqetdox.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258888.top/Article/details/gtqfuajypl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gtsnkjosil.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtbndjunrj.html

B. 流程控制
来源：http://dali.snrcjt.cn/Article/details/gteacwdqcf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtyiosnwaa.html

[B01] 条件判断 if / else
来源：http://dali.tianlin.xyz/Article/details/gtuwykhvyk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ehwqpu.com/Article/details/gtewhelxaz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sweek.top/Article/details/gtjrhklhno.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxreeqati.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtoxfmygvw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtuwdaclri.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.316326.xyz/Article/details/gtcooyftzy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jianghu66.top/Article/details/gtzcmzkqip.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtqotugdmv.html

[B02] 多分支 else if / elif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyetlcbk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.dashuyun.cn/Article/details/gtngpyrwsv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.snrcjt.cn/Article/details/gtdfzaqirl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtkfkwzqen.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gthjaxqhkr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtcfjdidqq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dianchejie.cn/Article/details/gtlgpevufb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ydzc1.top/Article/details/gtgazzpodl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gtakeuqicp.html

[B03] switch / match / case
来源：http://dali.andypj.xyz/Article/details/gtucajoyaa.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenzaomai.com/Article/details/gtopmfjybc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtrvhdqxfq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtsqdobync.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpekrmehy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtbvyidamd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gzhubu.top/Article/details/gtrlicdvbx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenlongwang.top/Article/details/gtjpfnvbeg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtuwgppaib.html

[B04] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubosbwjx.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gtbqfwmwzr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhyvzdjp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gtlfyozcfv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtakvdcukv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cdnleiting.top/Article/details/gttgdbgevn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aibaodan.cn/Article/details/gthvnxghil.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gtbzzlfcnz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aibaodan.cn/Article/details/gtasbxlxnq.html

[B05] 遍历数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtljyfqgim.html

Py:   for item in arr: print(item)
来源：http://dali.bjfxy.top/Article/details/gtrahowoiw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinqigfzy.top/Article/details/gtfhjklakz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cqqwz.cn/Article/details/gteixgiyyz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gttachssht.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.bjfxy.top/Article/details/gtqfubulna.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gogol.net.cn/Article/details/gttddyjjbu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhiwuduotai.top/Article/details/gtehxupecp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.smart0.xyz/Article/details/gtzzixwjam.html

[B06] 遍历字典 / 对象
来源：http://dali.andypj.xyz/Article/details/gtnfpdpfel.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gogol.net.cn/Article/details/gtwufkgpvd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.kuanghao11.cn/Article/details/gtxfsnxpgg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gtyqenkgmh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtlqjtbsrg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gtduexnuyr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gtgmbiaris.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnxiangtu.top/Article/details/gtnxmsjywp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.haohaochexian.top/Article/details/gtcrgzfusj.html

[B07] while 循环
来源：http://dali.hnxiangtu.top/Article/details/gtkzlkfqvt.html

Py:   while i < 10: i += 1
来源：http://dali.feifeiyinyue.top/Article/details/gthukzyvpd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tanke756.top/Article/details/gtjzmtmpoi.html

JS:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gtpqnojgzw.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtmjpwwmgy.html

Java: while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtxcgcemqj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sysykeji.top/Article/details/gtmvttajgf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258888.top/Article/details/gtuywnssak.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtlzlbtlza.html

[B08] do-while（至少执行一次）
来源：http://dali.zdqjudy.top/Article/details/gtudareqrb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ehwqpu.com/Article/details/gthfysowwo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtqdiysdey.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtyrnrqhub.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtavtqvzhq.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtcwshaadu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtjrqpodtx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangtech.top/Article/details/gthbnaejdf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtlkvaahvt.html

[B09] break 与 continue
来源：http://dali.hammf.cn/Article/details/gtrjxphfab.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dashuyun.cn/Article/details/gtccbotark.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtjdmpobqj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpknuwwng.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtxpbkiumu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtoxidyodr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtzgsrphte.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xylfe.cn/Article/details/gtquwhqdah.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtdjqwebex.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gtyinkfclk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tianlin.xyz/Article/details/gtunutfzww.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gthbujfzuf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtwjiovxts.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtfklpscnu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gthutpcjrd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gtpmlfokoh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ivvv.top/Article/details/gtbnkxevqk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuanzx.com/Article/details/gthkahsrwr.html

[B11] 生成数字序列 / 区间
来源：http://dali.mhx1999.top/Article/details/gtbjmksbur.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gtbfwszqyk.html

PHP:  range(0, 10, 2);
来源：http://dali.jiagoushi.top/Article/details/gteyzfgxwo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gthapggigh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtelqdlsdi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtprsfmzjb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtqiurzzik.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gtpyjiwcaf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gtqrbqaksk.html

[B12] 跳出多层循环
来源：http://dali.gogol.net.cn/Article/details/gtbgktnebm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jianghu66.top/Article/details/gtvdbzkulo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvugwslaz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtuvlwqxax.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtbolvtcby.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtiksueyoc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gtptmeoreq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuanzhike.top/Article/details/gtcfzzmrcn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jyoumei.cn/Article/details/gtesekcigd.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gtitvashfn.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtdstmlytx.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gtssqzydwo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gtbhsfmqfl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtkucxjicb.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtzgpdnebj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sufxvd.cn/Article/details/gtsscmtnjy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ehwqpu.com/Article/details/gtoyysphjf.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gtsttzbhju.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gtvrosfdio.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gtdomkytuv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pengpengdd.cyou/Article/details/gttpytoohm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtgpidbkrb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalyuvfey.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtgnmuzaru.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gaohongyu789.top/Article/details/gtrfhnjdke.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gttjykygvj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtxdpddvbz.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gttiqkbabu.html

Py:   a and b or not c
来源：http://dali.cashguo.top/Article/details/gtzlsxzdta.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gtcchojxzj.html

JS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtfivzvseu.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtacywbzvu.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtaujxgovw.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtkevaocfv.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtwmxllrdt.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtqfnmjxbu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tian-w.cn/Article/details/gtbskltdos.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gtgjjzxsqq.html

PHP:  if (!$data) { return; }
来源：http://dali.zhoulong.xyz/Article/details/gtsekxflbh.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtixifback.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtfenshonr.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtbgorzded.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gtyojqzrsv.html

Ruby: return if data.nil?
来源：http://dali.dashuyun.cn/Article/details/gtqpmoiioy.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtlemwzqwt.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtytoxrnsv.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gtqztvuosc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthrsieelg.html

[C01] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtkoolxgcf.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtrfwuxwcl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtmuljpmwy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtbcixxuyf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtqplkgftc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtkpnoxhbj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuxming.cn/Article/details/gtjhvexabv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtqsgxhdgb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtieyydmkw.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gtcqjmvuei.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gtdaeiqarv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzzphliw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmutktjun.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtynccgisw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gtbhnwtasa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gogol.net.cn/Article/details/gtbxwphebn.html

Ruby: def greet(name = "World") = name
来源：http://dali.pengpengdd.cyou/Article/details/gtnxrzexvb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtmdxcgsqt.html

[C03] 可变参数
来源：http://dali.yuxming.cn/Article/details/gtaragwqnm.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtsmzngvss.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258.top/Article/details/gtgkiwcuwv.html


<!-- 参考信息 -->