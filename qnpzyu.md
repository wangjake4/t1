代发 wailian999

[A14] 注释写法
来源：http://dali.xuanzx.com/Article/details/gt2reghiayo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jianghu66.top/Article/details/gt2dyksnzar.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhtotxpx.html

JS:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gt2vyibkbaz.html

TS:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gt2odekuoxf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sysykeji.top/Article/details/gt2jzdxzkxb.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gt2umkvzhdb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.aibaodan.cn/Article/details/gt2rbqxaeha.html

C#:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gt2ulzuriqh.html

[A15] 空值判断与默认值
来源：http://dali.yonumen.top/Article/details/gt2raknfrtm.html

Py:   value = data or "默认值"
来源：http://dali.gogol.net.cn/Article/details/gt2sqbkrtur.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gt2aefslgsj.html

JS:   const value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gt2icybfvjg.html

TS:   const value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gt2xhgumvtc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.fengsongda.top/Article/details/gt2zpgxjrqb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cheryme.top/Article/details/gt2llqmxizd.html

Ruby: value = data || "默认值"
来源：http://dali.daria6918.cn/Article/details/gt2fxmpfave.html

C#:   var value = data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gt2zvonvybh.html

[A16] 真假值判断规则
来源：http://dali.sysykeji.top/Article/details/gt2nsapglly.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hnxiangtu.top/Article/details/gt2quezguwz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pengpengdd.cyou/Article/details/gt2iuvkezby.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.dianchejie.cn/Article/details/gt2ziymckmc.html

TS:   if (!x) {}
来源：http://dali.pycfn.com/Article/details/gt2gtzubmdf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ycspepow.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.iojbl.cn/Article/details/gt2xzvfemsh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tanke756.top/Article/details/gt2xvwlgndz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ofhtzcvy.html

[A17] 位运算
来源：http://dali.hnqzz.top/Article/details/gt2xiwuwcft.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2kmltyfwt.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.aizwys.cn/Article/details/gt2zeranrde.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gt2zfbprznj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2qufizvxh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gt2cvjwljdy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gt2hciyfyfn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gt2fmladqkr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2prikzifm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sweek.top/Article/details/gt2gybdtqii.html

Py:   ord("A"); chr(65)
来源：http://dali.havefunace.top/Article/details/gt2jsiomaau.html

PHP:  ord("A"); chr(65)
来源：http://dali.jlsjyb.cn/Article/details/gt2dcgbrycu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gt2aownzrqr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.havefunace.top/Article/details/gt2frndkzju.html

Java: (int) 'A'; (char) 65
来源：http://dali.c1oappe.top/Article/details/gt2dzlzzsav.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sufxvd.cn/Article/details/gt2kinckreq.html

Ruby: "A".ord; 65.chr
来源：http://dali.zdqjudy.top/Article/details/gt2doqrhpnd.html

C#:   (int)'A'; (char)65
来源：http://dali.tianlin.xyz/Article/details/gt2wxpjvrwa.html

[A19] 交换两个变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkrsodkc.html

Py:   a, b = b, a
来源：http://dali.chenzaomai.com/Article/details/gt2gwmczqpy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xinyue.icu/Article/details/gt2gvxwswnw.html

JS:   [a, b] = [b, a];
来源：http://dali.yangfankeji.com/Article/details/gt2yngwhpbr.html

TS:   [a, b] = [b, a];
来源：http://dali.fengsongda.top/Article/details/gt2zvxukdpl.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbazfrcw.html

Go:   a, b = b, a
来源：http://dali.kuanghao11.cn/Article/details/gt2racejhvk.html

Ruby: a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gt2umylesmw.html

C#:   (a, b) = (b, a);
来源：http://dali.gogol.net.cn/Article/details/gt2ksfzhzsi.html

[A20] 读取标准输入
来源：http://dali.chenjidiqi.icu/Article/details/gt2skcvzyoo.html

Py:   name = input("请输入：")
来源：http://dali.xziqi.cn/Article/details/gt2aegyavhd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xuetiantiany.cn/Article/details/gt2kspfyhsp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuwdkolk.html

TS:   // Node.js：readline 模块
来源：http://dali.wangdashe.top/Article/details/gt2qlilwunv.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.sysykeji.top/Article/details/gt2zpgvnkfk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ybcxt.top/Article/details/gt2cbbxjhjo.html

Ruby: gets.chomp
来源：http://dali.yanxiufei.cn/Article/details/gt2hccqtady.html

C#:   Console.ReadLine();
来源：http://dali.yuanzhike.top/Article/details/gt2mzmwpsrz.html

[A21] 保留指定小数位输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzeahcbn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tianlin.xyz/Article/details/gt2ewkarypm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gt2umwofctz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gt2yynjsbbf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gt2cumljwlb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gt2genlpsaq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gt2hzxlwkpm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gt2uvejrzmk.html

C#:   3.14159.ToString("F2")
来源：http://dali.cashguo.top/Article/details/gt2pqjyktxq.html

[A22] 获取字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2ryycfsbf.html

Py:   len(s)
来源：http://dali.yongpay.top/Article/details/gt2nyeiboco.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjxxfaek.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tanke756.top/Article/details/gt2rgnqypvo.html

TS:   s.length
来源：http://dali.aibaodan.cn/Article/details/gt2gohxsxyt.html

Java: s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2lgneizys.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2eniugfgw.html

Ruby: s.length
来源：http://dali.hnqzz.top/Article/details/gt2zzbgmwhi.html

C#:   s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvgdvwzf.html

[A23] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2bslfwtkg.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2yubniqxq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuxming.cn/Article/details/gt2aalizuhq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xoissrpf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gt2klwoausy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gt2yavjehmq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gzhubu.top/Article/details/gt2pxwducwk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gt2fufqvcwt.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yuxming.cn/Article/details/gt2lsguaviw.html

[A24] 去除首尾空白
来源：http://dali.daxiang520.top/Article/details/gt2tvexewrf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xinyue.icu/Article/details/gt2ijsaijyh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xylfe.cn/Article/details/gt2lfgzeidv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gt2goqyiozi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gt2ubryjyxt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhiwuduotai.top/Article/details/gt2harcnfwg.html

Go:   strings.TrimSpace(s)
来源：http://dali.cqqwz.cn/Article/details/gt2cejkluiv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jyoumei.cn/Article/details/gt2ctfrqogz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj202588.top/Article/details/gt2hasfcbvq.html

[A25] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2hhsurlda.html

Py:   s1 == s2; s1 != s2
来源：http://dali.birdmap.top/Article/details/gt2aucnznzv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hysaishi.cn/Article/details/gt2aavnpchd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.iojbl.cn/Article/details/gt2llanrpls.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kyyestlj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jyoumei.cn/Article/details/gt2rcpnkczm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gt2pgxasfyn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sweek.top/Article/details/gt2zwqocbej.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigfzy.top/Article/details/gt2bcoqedjy.html

[A26] 类型转换总览
来源：http://dali.dashuyun.cn/Article/details/gt2wlkiyhkp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cqqwz.cn/Article/details/gt2cffcdrqc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.9152youxi.cn/Article/details/gt2nueyfbsy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.svipenyu.cn/Article/details/gt2cjdwwmua.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shzxlz.cn/Article/details/gt2rjotqdvn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenzaomai.com/Article/details/gt2lksxckqx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.svipenyu.cn/Article/details/gt2vrvmapzq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhiwuduotai.top/Article/details/gt2oizyocbm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gt2vlagqbua.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2hgiuxzls.html

B. 流程控制
来源：http://dali.sweek.top/Article/details/gt2fxshxghf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2tkabceyt.html

[B01] 条件判断 if / else
来源：http://dali.shuidangran.top/Article/details/gt2mqvxxhfb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jyoumei.cn/Article/details/gt2xlsvzebp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jyoumei.cn/Article/details/gt2ebathgay.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykctbhzb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gt2qqsfvxgj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gt2edlsdsva.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yangfankeji.com/Article/details/gt2cdtkujkh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jlsjyb.cn/Article/details/gt2jadfszyq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csohapqn.html

[B02] 多分支 else if / elif
来源：http://dali.xinyue.icu/Article/details/gt2dfpeiuqe.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.9152youxi.cn/Article/details/gt2zzvogbrb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhixingplan.top/Article/details/gt2ugkvldfe.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2qaxvdelr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gt2lnxlzdkl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gt2dnqtttjy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.snrcjt.cn/Article/details/gt2ngsbjwcn.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zdqjudy.top/Article/details/gt2vkwwgfoh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gt2rggfbfys.html

[B03] switch / match / case
来源：http://dali.aizwys.cn/Article/details/gt2lsaflkgp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.daxiang520.top/Article/details/gt2zxizidpd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gt2cthubqvv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gt2vlghslun.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gt2ixdjesxs.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfeqamax.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.bjfxy.top/Article/details/gt2muxcixvx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gt2qszpgfkt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gt2yieismtb.html

[B04] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gt2axjjtfcr.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gt2zrguftjm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgqydxuq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2glxhvtop.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2vykriqrj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuxming.cn/Article/details/gt2topgdmff.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jqgufenzy.top/Article/details/gt2hpsmpehj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.havefunace.top/Article/details/gt2hjcmkxgg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jianghu66.top/Article/details/gt2dtytutbx.html

[B05] 遍历数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gt2bnxojzkf.html

Py:   for item in arr: print(item)
来源：http://dali.zycfv.cn/Article/details/gt2bkphbhbo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gt2ikafeafx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gt2uelvxmif.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2geiwtskx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cucudq.cn/Article/details/gt2pchrfree.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gorfxfno.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gt2btjhzwhk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.bjfxy.top/Article/details/gt2dmtmjptp.html

[B06] 遍历字典 / 对象
来源：http://dali.yuanzhike.top/Article/details/gt2otntmmnk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.haohaochexian.top/Article/details/gt2ndoxblrm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbhqkpfp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gt2kdnrukkf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gt2fvjicpow.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yongpay.top/Article/details/gt2otrwifrr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xylfe.cn/Article/details/gt2ygsqobqj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gt2hohfwhsy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.redwolf501.top/Article/details/gt2hwbhunpf.html

[B07] while 循环
来源：http://dali.mhx1999.top/Article/details/gt2zmvpiizt.html

Py:   while i < 10: i += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufynorgy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pycfn.com/Article/details/gt2ifmnflfw.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gxgokhso.html

TS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2zwwymkdz.html

Java: while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gt2zmbackft.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.svipenyu.cn/Article/details/gt2coubeobp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gt2lnrphfof.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2grqdmxme.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnpeoefx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gt2tfuzsfkv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2cqebvbtl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2ohofkmhj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2vbmzoayt.html

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2ptvooqzq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gt2tlmnjdvw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cashguo.top/Article/details/gt2tktcvytk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2xzxhcuvo.html

[B09] break 与 continue
来源：http://dali.yvedp.cn/Article/details/gt2chjrhhcq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuanzx.com/Article/details/gt2nufaohgp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2bxobdmhm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2khldhlfq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2webruiyg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2npqdvixu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgfzy.top/Article/details/gt2iashtonx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xylfe.cn/Article/details/gt2dfttfdeq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vbrynttj.html

[B10] 遍历同时拿索引
来源：http://dali.hywenlv.cn/Article/details/gt2epatfapm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yongpay.top/Article/details/gt2yqqmqwzt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.daxiang520.top/Article/details/gt2fkvyeokh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gt2bqugufkf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gt2mxjqwesn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gt2ynawbtbe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenzaomai.com/Article/details/gt2wxzvsrcn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gt2vtqbghaf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhoulong.xyz/Article/details/gt2xyaprbbe.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gt2tjelwgjc.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gt2sefjroyf.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gt2lwtfywih.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gt2yaromyyv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2vrdmelwe.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2jgctpart.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gt2lwouqxng.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dianchejie.cn/Article/details/gt2gkfsetae.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gt2nphiohls.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghujbgad.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shzxlz.cn/Article/details/gt2idxdkotf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2plcibliw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2gjessmed.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gt2xfywrpvi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2zuaaijhj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.quarkkingdee.top/Article/details/gt2yigtlxux.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.316326.xyz/Article/details/gt2bvqrydxm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.haohaochexian.top/Article/details/gt2bszelkil.html

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gt2tipuvjqo.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcixlwwx.html

PHP:  is_numeric($x)
来源：http://dali.yj20258888.top/Article/details/gt2fpiwsfhj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gt2yftnpbdc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2husontze.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gt2lkbtdirz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gt2oaxnpdxw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gt2ajvgdhrw.html

C#:   x is int or double or decimal
来源：http://dali.ybcxt.top/Article/details/gt2elgncddz.html

[B14] 判断值是否在集合内
来源：http://dali.zhixingplan.top/Article/details/gt2usdihezs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gt2mbuwyyic.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gt2lirdnhnm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gt2nbgcgwej.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uushidbm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2myjusrbn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2bvskzavi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gt2kskxbtis.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2zevnfuqo.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gt2gntdmhlw.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gt2zmdgghxx.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqqherxl.html

JS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2ehdwdcjf.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2ewomfppz.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2rapippxx.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2ekwwejpc.html

Ruby: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2ihauybrw.html

C#:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2razyimov.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2amffqtnn.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gt2zqxypadx.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxuanxn.top/Article/details/gt2hntdwnbo.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vujscxxb.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gt2vudcclqj.html

Java: if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gt2hsnpxxdx.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gt2xyveuwdd.html

Ruby: return if data.nil?
来源：http://dali.nanxinkj.top/Article/details/gt2ipiewrox.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gt2bzjsiqzl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2xfslbrog.html

C. 函数与作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2srmenihd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2tolgqglh.html

[C01] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2nivfdlzo.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gt2aendjqxr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2lxdqcgzw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2brwlxerl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2sjabqmsu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2ssxhzdqh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gt2welgcpwj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gt2ixyqvzxi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2bfwapkch.html

[C02] 默认参数
来源：http://dali.yanxiufei.cn/Article/details/gt2gnwmnhwg.html

Py:   def greet(name="World"): return name
来源：http://dali.hnxiangtu.top/Article/details/gt2sdgoepqh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2lnycnbqa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2eevambbw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2uuxmxckg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gt2hkosxzss.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gt2jgtdxvmz.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gt2vjemujqk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cashguo.top/Article/details/gt2xqksghgm.html

[C03] 可变参数
来源：http://dali.yuxming.cn/Article/details/gt2yvbeusli.html

Py:   def total(*args): return sum(args)
来源：http://dali.cdnleiting.top/Article/details/gt2fqvfjlkp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gt2xdnlxfwv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aubvoppo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2caxxoehg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ehwqpu.com/Article/details/gt2ukjuwrnm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gt2bmfrrtxl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gt2hpfhbmzc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.birdmap.top/Article/details/gt2xgckrfah.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gt2gjegaacb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjiqhsk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gt2atenhrtd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2mozryjco.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sweek.top/Article/details/gt2xgglnfml.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gt2zsvqhdzu.html


<!-- 参考信息 -->