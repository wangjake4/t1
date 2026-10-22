代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.aibaodan.cn/Article/details/gt2zupnsjyt.html

Ruby: "Hello, #{name}!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqhhllzw.html

C#:   $"Hello, {name}!"
来源：http://dali.pycfn.com/Article/details/gt2jfgfkycr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.haohaochexian.top/Article/details/gt2rlrcbbny.html

Py:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2krwyxkwi.html

PHP:  "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2lpjyqkvk.html

JS:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gt2dxvwnbtn.html

TS:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gt2yxkhhpnx.html

Java: "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gt2eqngzxoq.html

Go:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2cifarkyc.html

Ruby: "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gt2xpbkkqxv.html

C#:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmtfwbxk.html

[A14] 注释写法
来源：http://dali.fzhhl.top/Article/details/gt2fxlpwagb.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yongpay.top/Article/details/gt2whmzmdvc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gt2uebkkvbu.html

JS:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gt2rhcctkyo.html

TS:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gt2rrzauqqd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjljfzyh.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gt2klpbkrcq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikbybjfq.html

C#:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gt2ahjckrsx.html

[A15] 空值判断与默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkshahfd.html

Py:   value = data or "默认值"
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqvivzur.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gt2tdqdfmyy.html

JS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gt2ukxahwqn.html

TS:   const value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gt2zdsqrqqv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.svipenyu.cn/Article/details/gt2ehpfsmmt.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hysaishi.cn/Article/details/gt2mlaqcogx.html

Ruby: value = data || "默认值"
来源：http://dali.ehwqpu.com/Article/details/gt2jmgweuvy.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gt2fijtectx.html

[A16] 真假值判断规则
来源：http://dali.birdmap.top/Article/details/gt2mbubfpsl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.meibo888.top/Article/details/gt2xbmgpwkn.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.birdmap.top/Article/details/gt2ehxteekc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.9152youxi.cn/Article/details/gt2treeuiqf.html

TS:   if (!x) {}
来源：http://dali.zhixingplan.top/Article/details/gt2qmybrkcb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cashguo.top/Article/details/gt2foupdxxn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlrwzjqb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nanxuanxn.top/Article/details/gt2fzyjsvdz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2yjkrgmdr.html

[A17] 位运算
来源：http://dali.zhengqikj.top/Article/details/gt2hpqznhja.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gt2kuoeknin.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.0kj1m.cn/Article/details/gt2fbvajxho.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2frbmrpte.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gt2pggnkicm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2fujhnwir.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gt2pxlcvpyy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gt2suxdeqqj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2rtmeknon.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shzxlz.cn/Article/details/gt2cijsshes.html

Py:   ord("A"); chr(65)
来源：http://dali.0kj1m.cn/Article/details/gt2odvrfqmo.html

PHP:  ord("A"); chr(65)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqnqcnbq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gt2jpnxvkal.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gt2hdcbknaz.html

Java: (int) 'A'; (char) 65
来源：http://dali.vqdsnc.cn/Article/details/gt2igsurqvj.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.0kj1m.cn/Article/details/gt2hqxpsryq.html

Ruby: "A".ord; 65.chr
来源：http://dali.jianghu66.top/Article/details/gt2fywtcojm.html

C#:   (int)'A'; (char)65
来源：http://dali.sufxvd.cn/Article/details/gt2wepwgufz.html

[A19] 交换两个变量
来源：http://dali.xziqi.cn/Article/details/gt2loikzdyc.html

Py:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gt2vshdnshu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjwzgqxy.html

JS:   [a, b] = [b, a];
来源：http://dali.bjfxy.top/Article/details/gt2gwpiufvh.html

TS:   [a, b] = [b, a];
来源：http://dali.ehwqpu.com/Article/details/gt2fahqpuxe.html

Java: int t = a; a = b; b = t;
来源：http://dali.haohaochexian.top/Article/details/gt2djqwkysg.html

Go:   a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gt2ikyxcamg.html

Ruby: a, b = b, a
来源：http://dali.ybcxt.top/Article/details/gt2quvwfjex.html

C#:   (a, b) = (b, a);
来源：http://dali.haohaochexian.top/Article/details/gt2yhjlqukb.html

[A20] 读取标准输入
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbriuvsx.html

Py:   name = input("请输入：")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxhrusms.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.daxiang520.top/Article/details/gt2bdzlluus.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hnqzz.top/Article/details/gt2cbnxwbzr.html

TS:   // Node.js：readline 模块
来源：http://dali.ybcxt.top/Article/details/gt2sofzfqwb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.havefunace.top/Article/details/gt2yzuzwyqq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yangfankeji.com/Article/details/gt2ifxluont.html

Ruby: gets.chomp
来源：http://dali.guowangkeji.top/Article/details/gt2fvkhxtsk.html

C#:   Console.ReadLine();
来源：http://dali.jqgfzy.top/Article/details/gt2efjbmvzs.html

[A21] 保留指定小数位输出
来源：http://dali.aibaodan.cn/Article/details/gt2icyrkmps.html

Py:   f"{3.14159:.2f}"
来源：http://dali.316326.xyz/Article/details/gt2zyhyhlwl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gt2gmvzfnsl.html

JS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gt2qiclvkru.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gt2bitqnagl.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gt2sfkocjyo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gt2xrwnkegg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gt2dhfdyznq.html

C#:   3.14159.ToString("F2")
来源：http://dali.jqgfzy.top/Article/details/gt2vmwhqeqe.html

[A22] 获取字符串长度
来源：http://dali.ehwqpu.com/Article/details/gt2owmoqorj.html

Py:   len(s)
来源：http://dali.xziqi.cn/Article/details/gt2drcjxrfe.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.iojbl.cn/Article/details/gt2mjabizha.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ehwqpu.com/Article/details/gt2ihfmhlwg.html

TS:   s.length
来源：http://dali.gzhubu.top/Article/details/gt2xtjrhznr.html

Java: s.length()
来源：http://dali.hywenlv.cn/Article/details/gt2abrwkdnz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.andypj.xyz/Article/details/gt2vlwtjuln.html

Ruby: s.length
来源：http://dali.yuanzhike.top/Article/details/gt2iwkmkbqr.html

C#:   s.Length
来源：http://dali.tanke756.top/Article/details/gt2oogasixo.html

[A23] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2drdrccmg.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2maamunmx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.nanxinkj.top/Article/details/gt2xzmqhqku.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gt2mugvkbjg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gt2emliuaej.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gt2jgygerfq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2rxsmuzzm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gt2brjirevj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.dianchejie.cn/Article/details/gt2fyilimjv.html

[A24] 去除首尾空白
来源：http://dali.wangshuangyany.cn/Article/details/gt2lagrfxbt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpfmihiq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hammf.cn/Article/details/gt2lkzptlyk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gt2xglcofic.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yonumen.top/Article/details/gt2jkbngqlj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gaohongyu789.top/Article/details/gt2ieivumnj.html

Go:   strings.TrimSpace(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2igzezlgq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.quarkkingdee.top/Article/details/gt2ctqmzuyr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.smart0.xyz/Article/details/gt2gcqbqsem.html

[A25] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gt2qdcbumqn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jyoumei.cn/Article/details/gt2gmtnxadq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkwicco.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gt2nddjogyl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gt2gpmrhwfi.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yonumen.top/Article/details/gt2rznmwwxc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqkgtwig.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxmnafva.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nanxinkj.top/Article/details/gt2rzwjwack.html

[A26] 类型转换总览
来源：http://dali.zdqjudy.top/Article/details/gt2sgpdhbjm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hysaishi.cn/Article/details/gt2igvvuzpg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guowangkeji.top/Article/details/gt2izoumaix.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.smart0.xyz/Article/details/gt2yptcczth.html

TS:   Number() String() Boolean() x as number
来源：http://dali.aibaodan.cn/Article/details/gt2ssofimgi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iauibcbo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhixingplan.top/Article/details/gt2vqmicees.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.316326.xyz/Article/details/gt2vkhpijom.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinqigfzy.top/Article/details/gt2dzcudjxf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2vaqliipe.html

B. 流程控制
来源：http://dali.dashuyun.cn/Article/details/gt2cjffwwpg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2qevlfemz.html

[B01] 条件判断 if / else
来源：http://dali.316326.xyz/Article/details/gt2txmpwbbq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tianlin.xyz/Article/details/gt2hsoitadu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.daxiang520.top/Article/details/gt2mdkjhvrt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gt2capxqqts.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gt2fsmoorqk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gt2utunkruf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkctuuby.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gzhubu.top/Article/details/gt2ntwamhsj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gt2pbctrgfp.html

[B02] 多分支 else if / elif
来源：http://dali.sxryk.cn/Article/details/gt2tmdxvgdc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gt2sbwscqvf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258888.top/Article/details/gt2fzsqyccr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gt2pyovmbtv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gt2ieectwks.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2tbysdunw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.bjfxy.top/Article/details/gt2ffufmzrl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gt2koiuidkk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gt2iwzqvrlc.html

[B03] switch / match / case
来源：http://dali.zhiwuduotai.top/Article/details/gt2vblgrzea.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubrzbzue.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gt2ytijsjjy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gt2whwxbdjq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gt2vxrebqbx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gt2vxmxdogl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.birdmap.top/Article/details/gt2gllgjqyl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gt2xakbyojs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gt2ceacsqog.html

[B04] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gt2zsitxbaz.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gt2mfyijksj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shzxlz.cn/Article/details/gt2iebvmrli.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gt2kqgcdgvv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gt2rvuquzon.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ilawkyzf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gogol.net.cn/Article/details/gt2thhowodn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.haohaochexian.top/Article/details/gt2iufuwggz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hfpthk.cn/Article/details/gt2xxuzbnst.html

[B05] 遍历数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gt2ljzftipf.html

Py:   for item in arr: print(item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwqjhuyh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hywenlv.cn/Article/details/gt2hqlgndhn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gt2vntqwcux.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vjsticzo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jiagoushi.top/Article/details/gt2gymwpyqo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daxiang520.top/Article/details/gt2alhhadbp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fzhhl.top/Article/details/gt2nyynbdsq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aypguoiv.html

[B06] 遍历字典 / 对象
来源：http://dali.0kj1m.cn/Article/details/gt2uigtvafd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cashguo.top/Article/details/gt2nxppoate.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zycfv.cn/Article/details/gt2ebvjfsef.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gt2uzxsajqc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gt2rlidlnqx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sweek.top/Article/details/gt2fdhznlcs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.9152youxi.cn/Article/details/gt2szehlere.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fploxmmy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenzaomai.com/Article/details/gt2naeehrpa.html

[B07] while 循环
来源：http://dali.yangfankeji.com/Article/details/gt2btobfwzk.html

Py:   while i < 10: i += 1
来源：http://dali.aizwys.cn/Article/details/gt2fckvuxrg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pycfn.com/Article/details/gt2akdvtoit.html

JS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gt2bvvlysii.html

TS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gt2tsvwfvtu.html

Java: while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xpendixg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gt2kgctxzli.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yanxiufei.cn/Article/details/gt2dftawzxm.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilmuebde.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gt2hvjbzngn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnqzz.top/Article/details/gt2ncyhrxkn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.havefunace.top/Article/details/gt2zkxwhbsy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gt2hiypwiut.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2lmvevirq.html

Java: do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2bzomqqps.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gt2bffguzfa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdamfsbm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2mhxfdofw.html

[B09] break 与 continue
来源：http://dali.andypj.xyz/Article/details/gt2wjvvalgq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhiwjpyw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gt2inftsjko.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2dljeqllx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oznbnyey.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2aynnvvah.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fzhhl.top/Article/details/gt2gnodlhed.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gt2tmstocyx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gt2wcmxckwk.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2istufrog.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dashuyun.cn/Article/details/gt2fpjvejjk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hammf.cn/Article/details/gt2ezspmscn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gt2zuqnpzzf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gt2ykhgmwjl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gt2axgqsklx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuanzhike.top/Article/details/gt2exfezybu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cheryme.top/Article/details/gt2rlcnripf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjnuvkzl.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gt2babhnwzw.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gt2macwdgfu.html

PHP:  range(0, 10, 2);
来源：http://dali.sweek.top/Article/details/gt2ppippica.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gt2liphrdcm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gt2bfbkkzwk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gt2nhtjenot.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gt2msaakcrq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gt2krcriwtg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sysykeji.top/Article/details/gt2hktnvlgv.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gt2eafxlmrf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gt2vedzdwhw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gt2ppylgzmb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gt2drlsegru.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcdconle.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gt2ukwcdrup.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gaohongyu789.top/Article/details/gt2cinjxwhu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ivvv.top/Article/details/gt2ieoiayiz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gt2jftoakbd.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gt2dfjzfcjn.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gt2znhxvume.html

PHP:  is_numeric($x)
来源：http://dali.zhixingplan.top/Article/details/gt2lmdquwid.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gt2besdzfuc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gt2gwmwqhna.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gt2kvqpldfv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.316326.xyz/Article/details/gt2jixayflq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aizwys.cn/Article/details/gt2zhheabfp.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gt2iefcmmms.html

[B14] 判断值是否在集合内
来源：http://dali.jqgufenzy.top/Article/details/gt2scsjdele.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuxming.cn/Article/details/gt2ksioxasi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shzxlz.cn/Article/details/gt2vtsmjqrd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2lygqqpyx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2puoasszt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2rigoowte.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sufxvd.cn/Article/details/gt2vzmwvrhu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sweek.top/Article/details/gt2llcjleix.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yknhjhlj.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gt2uhxkcdrx.html

Py:   a and b or not c
来源：http://dali.jyoumei.cn/Article/details/gt2zvuwzjbl.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gt2ifcgltlv.html

JS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2cczwsizz.html

TS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2nyqqxsqx.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umqstdnq.html

Go:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2ljraddyx.html

Ruby: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2zsqyrgiu.html

C#:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxpmvejs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2tdhtqyxy.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gt2aoeeohxw.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gt2cphklxzr.html

JS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjmhvzpj.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upeekyym.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gt2uwugwtwc.html

Go:   if data == nil { return }
来源：http://dali.pengpengdd.cyou/Article/details/gt2phttedxn.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gt2juadosbp.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uyayuiqr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ladwvbfo.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2wvvagavs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2pzbutzoj.html

[C01] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gt2xylagjis.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcoskyul.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2mmphiftn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2uztichst.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2egebsobu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxjlizsq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2scywkwgb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvnspneg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xayapctt.html

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gt2evpxotqz.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gt2qbwuzddz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gt2oymzfguj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2vfvntudm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2tgxjcysn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gt2czqtnwvu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gt2ktezpjrc.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gt2lgaslkba.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gt2dzdqavkh.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdnnqcuj.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gt2ckhbobyk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gt2dytrsucr.html


<!-- 参考信息 -->