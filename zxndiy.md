代发 wailian999

[A14] 注释写法
来源：http://dali.hnxiangtu.top/Article/details/gt2fsjsanqj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ybcxt.top/Article/details/gt2chstjhwn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2bqkpoctz.html

JS:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gt2jqdjyrwg.html

TS:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gt2imctzzga.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.c1oappe.top/Article/details/gt2thzuvtlh.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gt2gwszytcz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ppjwa.cn/Article/details/gt2ffjpdxnh.html

C#:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gt2qgfgvdbg.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfapywzf.html

Py:   value = data or "默认值"
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqvhpmbn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gt2cdlhaqkw.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2mdglohju.html

TS:   const value = data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gt2xjtnutzo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kygaljkt.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jqgfzy.top/Article/details/gt2dsksecxt.html

Ruby: value = data || "默认值"
来源：http://dali.guannengcc.top/Article/details/gt2mpyppwjt.html

C#:   var value = data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gt2pjxztydu.html

[A16] 真假值判断规则
来源：http://dali.zhiwuduotai.top/Article/details/gt2btedbobf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhixingplan.top/Article/details/gt2nyutlqev.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sysykeji.top/Article/details/gt2mlxktnmm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.dashuyun.cn/Article/details/gt2zjwipklf.html

TS:   if (!x) {}
来源：http://dali.ppjwa.cn/Article/details/gt2qyxbkkmz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrcgdhsp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.redwolf501.top/Article/details/gt2ujqrdwsh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gotoacloud.top/Article/details/gt2mufoarcg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xziqi.cn/Article/details/gt2ezzzouwk.html

[A17] 位运算
来源：http://dali.shzxlz.cn/Article/details/gt2izknqnqf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gt2vbiqiktt.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2dkcvnwaw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2twnzkovw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gt2rxzhneej.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjmbcdt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2fkevhxrh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gt2biylnirl.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2yotpyfxr.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rooiuadc.html

Py:   ord("A"); chr(65)
来源：http://dali.c1oappe.top/Article/details/gt2ydajowpt.html

PHP:  ord("A"); chr(65)
来源：http://dali.aibaodan.cn/Article/details/gt2ouquhwuf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ydzc1.top/Article/details/gt2mtxalroe.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pycfn.com/Article/details/gt2dakvvegx.html

Java: (int) 'A'; (char) 65
来源：http://dali.birdmap.top/Article/details/gt2kixokdyr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfbciazr.html

Ruby: "A".ord; 65.chr
来源：http://dali.ivvv.top/Article/details/gt2pvcxcqjg.html

C#:   (int)'A'; (char)65
来源：http://dali.xuanzx.com/Article/details/gt2byvevrfw.html

[A19] 交换两个变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gspfoofp.html

Py:   a, b = b, a
来源：http://dali.jqgfzy.top/Article/details/gt2gbchmomn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guowangkeji.top/Article/details/gt2bwbykbmv.html

JS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gt2jnmryvoq.html

TS:   [a, b] = [b, a];
来源：http://dali.yanxiufei.cn/Article/details/gt2elfqdoqr.html

Java: int t = a; a = b; b = t;
来源：http://dali.sweek.top/Article/details/gt2tsutmvfs.html

Go:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2baeyqmzg.html

Ruby: a, b = b, a
来源：http://dali.316326.xyz/Article/details/gt2nxdsrsur.html

C#:   (a, b) = (b, a);
来源：http://dali.bjfxy.top/Article/details/gt2zbuxlyhr.html

[A20] 读取标准输入
来源：http://dali.jiagoushi.top/Article/details/gt2lupecvul.html

Py:   name = input("请输入：")
来源：http://dali.hnxiangtu.top/Article/details/gt2ekqfptrw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aizwys.cn/Article/details/gt2ffkymtok.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xinyue.icu/Article/details/gt2joermoam.html

TS:   // Node.js：readline 模块
来源：http://dali.zhixingplan.top/Article/details/gt2mcmcrfhg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdetwjtp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwbyriyj.html

Ruby: gets.chomp
来源：http://dali.sweek.top/Article/details/gt2xwnwoxwe.html

C#:   Console.ReadLine();
来源：http://dali.bjfxy.top/Article/details/gt2hxumplbz.html

[A21] 保留指定小数位输出
来源：http://dali.nwbrower.top/Article/details/gt2qvokbqoi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.wangdashe.top/Article/details/gt2aqelwmky.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gt2uuiypkau.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtmiixlt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2gtozknst.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gt2osddwrmj.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gt2ziyjtigj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gt2vqfzeesn.html

C#:   3.14159.ToString("F2")
来源：http://dali.daria6918.cn/Article/details/gt2uatardmh.html

[A22] 获取字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgjgsjce.html

Py:   len(s)
来源：http://dali.zycfv.cn/Article/details/gt2qmbpekdt.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yuanzhike.top/Article/details/gt2bcskvufj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.haohaochexian.top/Article/details/gt2lkmykvhi.html

TS:   s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2operoiyk.html

Java: s.length()
来源：http://dali.dashuyun.cn/Article/details/gt2hnlsatme.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.mhx1999.top/Article/details/gt2hzorflqd.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gt2hcepmbai.html

C#:   s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2skazxaxn.html

[A23] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2zpdbtzhp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ydzc1.top/Article/details/gt2bwxekxtc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhengqikj.top/Article/details/gt2otrovugx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gt2ktwamtmh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gt2mxuycmkt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gt2ygmvmdiw.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2wdbydnhn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybgieuqg.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.fengsongda.top/Article/details/gt2hkdvzcww.html

[A24] 去除首尾空白
来源：http://dali.yueranfly.top/Article/details/gt2vddtkxqa.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkohqghb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenzaomai.com/Article/details/gt2owusszmx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gt2cngtzcwi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.meibo888.top/Article/details/gt2utmgssyd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nwbrower.top/Article/details/gt2npltzoeh.html

Go:   strings.TrimSpace(s)
来源：http://dali.zdqjudy.top/Article/details/gt2qlrxhgol.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shuidangran.top/Article/details/gt2jieoucft.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hfpthk.cn/Article/details/gt2amgwjjwt.html

[A25] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2bnyxhomy.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cdnleiting.top/Article/details/gt2dnajivvy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ppjwa.cn/Article/details/gt2fofvgdai.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gt2ipwkkhzf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guowangkeji.top/Article/details/gt2iosmnzcy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fzhhl.top/Article/details/gt2voypkdnf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byuvcwaj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxklpuwd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgzfmro.html

[A26] 类型转换总览
来源：http://dali.andypj.xyz/Article/details/gt2ozkfthqk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangdashe.top/Article/details/gt2gxikfudk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daria6918.cn/Article/details/gt2axcuvgtd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgfzy.top/Article/details/gt2uyvdsfds.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gaohongyu789.top/Article/details/gt2qxvwtsat.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gt2bnfdwtsd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2rcknouvd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tianlin.xyz/Article/details/gt2bmiklpkj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gt2zjhwfndf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ouaidpli.html

B. 流程控制
来源：http://dali.hfpthk.cn/Article/details/gt2nlxlcsaf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2oxgoopuw.html

[B01] 条件判断 if / else
来源：http://dali.havefunace.top/Article/details/gt2uzwhrovv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.havefunace.top/Article/details/gt2hixazeot.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.bjfxy.top/Article/details/gt2apcgpfhb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gt2ltlwvfvz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2smgqnmau.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gt2ezzejuqi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.haohaochexian.top/Article/details/gt2dnreowbg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.pengpengdd.cyou/Article/details/gt2uootronl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gt2tkvkjewu.html

[B02] 多分支 else if / elif
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcnnjwse.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangdashe.top/Article/details/gt2ccjxtrhm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.guannengcc.top/Article/details/gt2icbeaqsm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gt2jzstbubn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gt2ejjasbfs.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gt2vcvjeqnt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jqgfzy.top/Article/details/gt2wyseuybk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pycfn.com/Article/details/gt2yuqvzaxx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2avsfvkaw.html

[B03] switch / match / case
来源：http://dali.xylfe.cn/Article/details/gt2cvabynnj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.c1oappe.top/Article/details/gt2ernenaek.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gt2bmljvsdt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dglmwxau.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gt2oqdwldoz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vufkuqvr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zycfv.cn/Article/details/gt2aqmsfdib.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.svipenyu.cn/Article/details/gt2jjmsqsaf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzunipmb.html

[B04] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gt2asidyrpv.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gt2kclqrkyo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zdqjudy.top/Article/details/gt2tztplrry.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gt2abmrpdkc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gt2plxzbpwa.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ivvv.top/Article/details/gt2jxrlymgd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guannengcc.top/Article/details/gt2ipbfmdah.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sysykeji.top/Article/details/gt2stpbsdto.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2chuwwsal.html

[B05] 遍历数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxoagiyj.html

Py:   for item in arr: print(item)
来源：http://dali.yangfankeji.com/Article/details/gt2remvwegl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yongpay.top/Article/details/gt2fssfjpbh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gt2tewuuzzo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhengqikj.top/Article/details/gt2ohzwqlpx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnqzz.top/Article/details/gt2ustyacsb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.andypj.xyz/Article/details/gt2pwmdmbzq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpbkdhn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulbtftbm.html

[B06] 遍历字典 / 对象
来源：http://dali.hysaishi.cn/Article/details/gt2cdmohxnd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ehwqpu.com/Article/details/gt2hpxsrlvg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.redwolf501.top/Article/details/gt2lhwopghi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gt2sunovqki.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gt2okkyizqy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cheryme.top/Article/details/gt2vhqomrst.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gt2qfxbukcj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigfzy.top/Article/details/gt2ntconpaf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258888.top/Article/details/gt2rjoenbmf.html

[B07] while 循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mawuutal.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gt2vlfzurij.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gt2uhfbeygo.html

JS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gt2snznxsls.html

TS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gt2emhxwsvb.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gt2dweikfxu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xinyue.icu/Article/details/gt2atvbyrqy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxinkj.top/Article/details/gt2hrfjrhvv.html

C#:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gt2arwentzw.html

[B08] do-while（至少执行一次）
来源：http://dali.9152youxi.cn/Article/details/gt2kkvlhusz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.mhx1999.top/Article/details/gt2igtvkwpo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2gqtchsyq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2vaokbydj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2amssdhbe.html

Java: do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2oterrzcq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shzxlz.cn/Article/details/gt2vqwqllgw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gt2vqhhgyug.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2wanifxah.html

[B09] break 与 continue
来源：http://dali.hammf.cn/Article/details/gt2hxxmfxfq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhongyouzk.top/Article/details/gt2xtcapwdn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2vyylxcdo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gt2mxmcbezo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2jfdewoua.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2cwhzszaf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykvdbqqp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sufxvd.cn/Article/details/gt2ddpqzsru.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2roszblsz.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigufen.top/Article/details/gt2uopoqqly.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gt2abmnromr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fengsongda.top/Article/details/gt2wcbrarwp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gt2fmefzxcr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gt2itjrhnxb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gt2feqkxwjn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gt2oalowwqm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yanxiufei.cn/Article/details/gt2vrotommw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gt2olbddhwr.html

[B11] 生成数字序列 / 区间
来源：http://dali.hammf.cn/Article/details/gt2wwphbayq.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulqaqftw.html

PHP:  range(0, 10, 2);
来源：http://dali.ydzc1.top/Article/details/gt2lvjbejup.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpyclokg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gt2nsrlljww.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aizwys.cn/Article/details/gt2eftgkhbr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhengqikj.top/Article/details/gt2fkpzabqq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fzhhl.top/Article/details/gt2ulynqvpm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gt2xwzskngs.html

[B12] 跳出多层循环
来源：http://dali.nwbrower.top/Article/details/gt2bjxzrtzc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gt2fdmnjlsg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gt2eamqobza.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gt2wokzimcd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njimmffo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdqpgxaj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.0kj1m.cn/Article/details/gt2itqicahq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gt2xtvcbosq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gt2lmmubzno.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gt2iwrxtbtp.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gt2uveoaqxp.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gt2ocpsksnj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gt2wijvuoxh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gt2sfignegp.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gt2njvittcq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jyoumei.cn/Article/details/gt2kixlamng.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhoulong.xyz/Article/details/gt2vntmgqkm.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gt2urvzntsr.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gt2qfnmgoby.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xinyue.icu/Article/details/gt2sayordca.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vounfnax.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2mzqhukml.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2dtqybaxm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gt2idljcele.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gt2jtomclfa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2iloxodan.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2crrvacrh.html

[B15] 布尔运算与取反
来源：http://dali.jyoumei.cn/Article/details/gt2ozlxthec.html

Py:   a and b or not c
来源：http://dali.wangshuangyany.cn/Article/details/gt2ueegizhm.html

PHP:  $a && $b || !$c
来源：http://dali.sysykeji.top/Article/details/gt2sixdrumv.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2xepaofnu.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2umzzrhhy.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2vhdbkzyt.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2chqnnnfb.html

Ruby: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2omuxfphk.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2vipjnmbo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtyxqahn.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gt2yzckpihh.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gt2rcerprjr.html

JS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2camezdvw.html

TS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2tbaonxpj.html

Java: if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gt2srpaojgp.html

Go:   if data == nil { return }
来源：http://dali.xuanzx.com/Article/details/gt2fftqnbvw.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gt2fewxtaoh.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gt2aposcxcm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2jlpatncp.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gt2nzbadwio.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2qwbymgie.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2qmuibyti.html

Py:   def add(a, b): return a + b
来源：http://dali.yongpay.top/Article/details/gt2qyndmgym.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2tcexbgsw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2bjgesbxw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2xtfvqryg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2szvevdzh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zycfv.cn/Article/details/gt2cfgdyvjp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gt2dviamcro.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2txhilycp.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gt2enshdohi.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gt2cjjvdshh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gt2imefdhnp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2fjxaydjn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lechljpn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gt2ctokbjni.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gt2obatyxoz.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gt2ewjcqecy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gt2slrsbgdg.html

[C03] 可变参数
来源：http://dali.ybcxt.top/Article/details/gt2bllyenrk.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gt2rlkyqsnu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gt2usjbbhfv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gt2imbwnvnw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gt2lpocrrvc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shuidangran.top/Article/details/gt2jkzslzhv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gt2wewdbrhc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gt2ccxgpmkb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenzaomai.com/Article/details/gt2bciteuuj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gt2czzmwpdt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcsklzwy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gt2zdfekrcm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gt2bnqqxlax.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gt2fzlhcznc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gt2nznwqolt.html


<!-- 参考信息 -->