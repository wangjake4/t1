代发 wailian999

[A14] 注释写法
来源：http://dali.cucudq.cn/Article/details/gt2cmzyntrk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zdqjudy.top/Article/details/gt2eauxcsnx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2sgvakdop.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjbzwywx.html

TS:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gt2jlyqlrjd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj202588.top/Article/details/gt2acphocby.html

Go:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gt2iccttkmb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlifdxlm.html

C#:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gt2zhqsompf.html

[A15] 空值判断与默认值
来源：http://dali.zhixingplan.top/Article/details/gt2tjlahone.html

Py:   value = data or "默认值"
来源：http://dali.aibaodan.cn/Article/details/gt2degytswb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwllaxdp.html

JS:   const value = data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gt2nloynmzq.html

TS:   const value = data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gt2fhmtawol.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crwwhttb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj20258888.top/Article/details/gt2bzacshxk.html

Ruby: value = data || "默认值"
来源：http://dali.yj202588.top/Article/details/gt2bawioxio.html

C#:   var value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oraxmaax.html

[A16] 真假值判断规则
来源：http://dali.yueranfly.top/Article/details/gt2ncjguigf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmgaysrw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.snrcjt.cn/Article/details/gt2vfnkurfl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xuanzx.com/Article/details/gt2fuhoijbb.html

TS:   if (!x) {}
来源：http://dali.bjfxy.top/Article/details/gt2tdastwhy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ljwvtopy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.bjfxy.top/Article/details/gt2ccerkzqd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2funfvvjd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daxiang520.top/Article/details/gt2wupeimur.html

[A17] 位运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcqlowbq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gt2blmenffk.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2cxuqmhdv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2wutvpaya.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gt2oxrsqojo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svgglrpi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2vfojwxsj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2xctioqsk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gt2ppovkudk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jlsjyb.cn/Article/details/gt2ekwebspt.html

Py:   ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gt2qanmauhd.html

PHP:  ord("A"); chr(65)
来源：http://dali.haohaochexian.top/Article/details/gt2zkxlgfjq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangdashe.top/Article/details/gt2gofpmnyp.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shzxlz.cn/Article/details/gt2ibizplts.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuetiantiany.cn/Article/details/gt2zuumfrxh.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jlsjyb.cn/Article/details/gt2tpzisxsa.html

Ruby: "A".ord; 65.chr
来源：http://dali.sweek.top/Article/details/gt2azyoujnh.html

C#:   (int)'A'; (char)65
来源：http://dali.pycfn.com/Article/details/gt2xlaytijh.html

[A19] 交换两个变量
来源：http://dali.gzhubu.top/Article/details/gt2wapczqrx.html

Py:   a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gt2jpkhieke.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.iojbl.cn/Article/details/gt2tegdirgj.html

JS:   [a, b] = [b, a];
来源：http://dali.chenlongwang.top/Article/details/gt2nccbmhta.html

TS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gt2etmzctwl.html

Java: int t = a; a = b; b = t;
来源：http://dali.nwbrower.top/Article/details/gt2gzozegzn.html

Go:   a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dyrlvxws.html

Ruby: a, b = b, a
来源：http://dali.yuxming.cn/Article/details/gt2wlwetdkf.html

C#:   (a, b) = (b, a);
来源：http://dali.dashuyun.cn/Article/details/gt2apuaaodv.html

[A20] 读取标准输入
来源：http://dali.cheryme.top/Article/details/gt2zdzyjddr.html

Py:   name = input("请输入：")
来源：http://dali.quarkkingdee.top/Article/details/gt2cuzmfqyt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hywenlv.cn/Article/details/gt2qofwpofj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shangyingyoupin.top/Article/details/gt2opcrnciw.html

TS:   // Node.js：readline 模块
来源：http://dali.chenzaomai.com/Article/details/gt2qikqndyt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.c1oappe.top/Article/details/gt2pzdxqxfl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hnxiangtu.top/Article/details/gt2nnbkctfj.html

Ruby: gets.chomp
来源：http://dali.hfpthk.cn/Article/details/gt2srnpkbfj.html

C#:   Console.ReadLine();
来源：http://dali.guowangkeji.top/Article/details/gt2ztemjazz.html

[A21] 保留指定小数位输出
来源：http://dali.haohaochexian.top/Article/details/gt2qqilhman.html

Py:   f"{3.14159:.2f}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfmjdbwc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2joozdklt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gt2zfwjdobc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2heblsfnr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2lvjopbrs.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxvanylt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gt2efpjdlkm.html

C#:   3.14159.ToString("F2")
来源：http://dali.yuanzhike.top/Article/details/gt2dmrukwaw.html

[A22] 获取字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2utnftriy.html

Py:   len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gttoowka.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.9152youxi.cn/Article/details/gt2budpqagi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jianghu66.top/Article/details/gt2yrnouhuu.html

TS:   s.length
来源：http://dali.meibo888.top/Article/details/gt2urhnjcgj.html

Java: s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2edwrfjgh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.andypj.xyz/Article/details/gt2mfnmssof.html

Ruby: s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2bolugkkj.html

C#:   s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2qphyabih.html

[A23] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2loxmfifk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yongpay.top/Article/details/gt2klvcdebv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqywjcid.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tffaadxi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gt2zrvpiazm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gt2xouhbbif.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daria6918.cn/Article/details/gt2jveqlgea.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sysykeji.top/Article/details/gt2tewtevwe.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.snrcjt.cn/Article/details/gt2jrilpblk.html

[A24] 去除首尾空白
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkkiwcfq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigfzy.top/Article/details/gt2hpudsdsv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yonumen.top/Article/details/gt2gvqscghy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gt2mtqfcnqf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cashguo.top/Article/details/gt2zuqpkszj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yuxming.cn/Article/details/gt2vqohefns.html

Go:   strings.TrimSpace(s)
来源：http://dali.0kj1m.cn/Article/details/gt2gvrqxmkh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.smart0.xyz/Article/details/gt2jcjywxwf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ivvv.top/Article/details/gt2xttcayxd.html

[A25] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2dqitpvdz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhijiandao.cn/Article/details/gt2nosyjbcn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbdstcys.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibpwibeg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gt2blfuhfst.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pikhmzyh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cdnleiting.top/Article/details/gt2sppdesdc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnzwxamo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gt2rouqrpbg.html

[A26] 类型转换总览
来源：http://dali.sysykeji.top/Article/details/gt2pxakcpuz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yvedp.cn/Article/details/gt2sklzfegi.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guowangkeji.top/Article/details/gt2yugfdtyb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhengqikj.top/Article/details/gt2fpuudjvt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yonumen.top/Article/details/gt2ndgpwcwh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijimmicg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxuanxn.top/Article/details/gt2olprigfs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yonumen.top/Article/details/gt2ooczpfcl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gt2aetxqubr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2cdzvfhfn.html

B. 流程控制
来源：http://dali.snrcjt.cn/Article/details/gt2rwvxqnwe.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2qgvsahdo.html

[B01] 条件判断 if / else
来源：http://dali.dianchejie.cn/Article/details/gt2xfqahsyx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.9152youxi.cn/Article/details/gt2etmpjjji.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hojxywvo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gt2ghrakzcf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2heieoomw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gt2cvgnuduc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gogol.net.cn/Article/details/gt2imvbeasj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shzxlz.cn/Article/details/gt2oulfxiie.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gt2aossboih.html

[B02] 多分支 else if / elif
来源：http://dali.yj202588.top/Article/details/gt2qljyyrof.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thxsxeap.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ivvv.top/Article/details/gt2kqpmdxso.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gt2pbvmdrax.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2ttetpucd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcczsvqi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.c1oappe.top/Article/details/gt2ynypwukr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dianchejie.cn/Article/details/gt2htivgpof.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvoobssu.html

[B03] switch / match / case
来源：http://dali.fengsongda.top/Article/details/gt2qeocxmog.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.quarkkingdee.top/Article/details/gt2wtojcdhj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vqcojdmw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gt2fgsdthnl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2yjobzusc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pynmsidk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2enwmwonb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fzhhl.top/Article/details/gt2goescfba.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yonumen.top/Article/details/gt2xysdvqmc.html

[B04] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gt2luzruigb.html

Py:   for i in range(10): print(i)
来源：http://dali.sxryk.cn/Article/details/gt2uagdokdn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sysykeji.top/Article/details/gt2nsybwfch.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2xshzrady.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gt2ioaswfxy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuxming.cn/Article/details/gt2nhdkndfb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkxqfims.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gt2jqwgaoqx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwcurgaa.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gt2tvteezei.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gt2lljthewk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cucudq.cn/Article/details/gt2uazbzwwh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gt2owxaijsf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gt2tkdyeugr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpanxwun.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnxiangtu.top/Article/details/gt2nagxwccs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2odjiyxwh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jlsjyb.cn/Article/details/gt2xewwmrst.html

[B06] 遍历字典 / 对象
来源：http://dali.ehwqpu.com/Article/details/gt2qecpcbta.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hysaishi.cn/Article/details/gt2lmmsahqw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aibaodan.cn/Article/details/gt2ruouxvyd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.andypj.xyz/Article/details/gt2szpmhjgl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gt2ukxfizjs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gt2nznfzvcd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aizwys.cn/Article/details/gt2ppolsmpi.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.c1oappe.top/Article/details/gt2wzqfmlri.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shuidangran.top/Article/details/gt2bedrcibc.html

[B07] while 循环
来源：http://dali.jqgfzy.top/Article/details/gt2mybqitue.html

Py:   while i < 10: i += 1
来源：http://dali.sysykeji.top/Article/details/gt2ncbsdnku.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymrmjcsa.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2xlmdlsxq.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gt2ozkkbifb.html

Java: while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2bzqcufeb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.kuanghao11.cn/Article/details/gt2lcruopau.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zycfv.cn/Article/details/gt2rkkiedcc.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2xgcssyfy.html

[B08] do-while（至少执行一次）
来源：http://dali.9152youxi.cn/Article/details/gt2bucwrpha.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gt2vkdtoftz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2lcefpjbu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2kkrvdtha.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2gokwpjgu.html

Java: do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2tnlnpnbb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gt2ympjjkgo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gt2bbxmzerz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2ykphhnsk.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gt2ovodfrqr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shuidangran.top/Article/details/gt2xlnayuns.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gt2ixhmuvov.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ogaejyvn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gt2jbrhyrgs.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gt2qhirjmod.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sweek.top/Article/details/gt2espekxaj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuxming.cn/Article/details/gt2xhpscmjv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxacsheo.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gt2vuafjgau.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gt2ihebxfey.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mglveoeo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gt2xbtlbmzu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msumrcej.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgfzy.top/Article/details/gt2rlelylzl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gt2zhxcfpdm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gt2bmmsccjf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2skusjxtm.html

[B11] 生成数字序列 / 区间
来源：http://dali.gaohongyu789.top/Article/details/gt2lpqzypkz.html

Py:   list(range(0, 10, 2))
来源：http://dali.guowangkeji.top/Article/details/gt2tqvzjwni.html

PHP:  range(0, 10, 2);
来源：http://dali.yvedp.cn/Article/details/gt2uccbhmcg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gt2bgrssxaf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gt2osactjkw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuanzx.com/Article/details/gt2enmkfdux.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hfpthk.cn/Article/details/gt2bheracmm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbhzywwm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tanke756.top/Article/details/gt2yekhizyr.html

[B12] 跳出多层循环
来源：http://dali.snrcjt.cn/Article/details/gt2dcxlojxb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gt2pzrnkjan.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fengsongda.top/Article/details/gt2ilzoklvh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2lreewgup.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gt2tkcextby.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gt2nsopgcft.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2caqhibru.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gt2oietbkcg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gt2zndvfvhw.html

[B13] 判断是否为数字
来源：http://dali.cashguo.top/Article/details/gt2peoymmdm.html

Py:   isinstance(x, (int, float))
来源：http://dali.fengsongda.top/Article/details/gt2xrsdjody.html

PHP:  is_numeric($x)
来源：http://dali.cucudq.cn/Article/details/gt2tjgtelnq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixfkssuf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2iqmvoxkh.html

Java: x instanceof Number
来源：http://dali.zycfv.cn/Article/details/gt2rrebnbyt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqxyiyuj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gt2onnbbizw.html

C#:   x is int or double or decimal
来源：http://dali.jinqigufen.top/Article/details/gt2mfxnglpw.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gt2dzdfvbyu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gt2neugjpoq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hstygccv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2urrpynbc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2mdpxcvct.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2vgocsuje.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gt2kdzjdopk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfuwcqcm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzxktorf.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gt2rvcqdxyh.html

Py:   a and b or not c
来源：http://dali.guannengcc.top/Article/details/gt2mappnxkp.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gt2tkftlgud.html

JS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2vaymtgzt.html

TS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2myeaqync.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2prosdfph.html

Go:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2lzlvqecm.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2ssujfcud.html

C#:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2tigzebrg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gt2wmyapxwf.html

Py:   if not data: return
来源：http://dali.haohaochexian.top/Article/details/gt2qnipmodt.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gt2yeayesbl.html

JS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gt2jyyagnyl.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gt2dpnfdofl.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gt2lissaqaz.html

Go:   if data == nil { return }
来源：http://dali.nanxinkj.top/Article/details/gt2hddarxds.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gt2bieibwot.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gt2ytqjfdqb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2aolbpzbm.html

C. 函数与作用域
来源：http://dali.tanke756.top/Article/details/gt2stjcwrce.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2msyeepuw.html

[C01] 定义函数
来源：http://dali.yuxming.cn/Article/details/gt2mpqxlpgv.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gt2degkceqb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2yrmigoau.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2thzqsizc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2siwtsfyl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2bvtiphdv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2pkacytnr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gt2tufpyjcc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2cgsruvwd.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvmzekle.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gt2qxtsigli.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gt2elhfmegz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2xlqponyf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2aienlpqr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gt2fqupikpr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dianchejie.cn/Article/details/gt2rrbmpume.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gt2fyghtsfr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gt2pvaiwcob.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gt2zgeuubzc.html

Py:   def total(*args): return sum(args)
来源：http://dali.zdqjudy.top/Article/details/gt2cgdxfver.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gt2jrhdgazo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2kogfnkqu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gt2sdfkobby.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2mykfnxbo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tianlin.xyz/Article/details/gt2ilmprxvl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tian-w.cn/Article/details/gt2nffiycxz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyivxoce.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gt2wpqinrpf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gt2wpgxrkob.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigufen.top/Article/details/gt2oyubpgpi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gt2qkikxuew.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gt2bypmyjhs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gt2laagxtvo.html


<!-- 参考信息 -->