代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2sdmhbraj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2uqggweqy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdmcgsxt.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gt2fiuqcdhf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nanxinkj.top/Article/details/gt2tlgpuyez.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigufen.top/Article/details/gt2qlxdrqzl.html

PHP:  ord("A"); chr(65)
来源：http://dali.ehwqpu.com/Article/details/gt2jcmawsac.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrxxissu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sxryk.cn/Article/details/gt2xfxmmqph.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhoulong.xyz/Article/details/gt2tfddbcvw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hammf.cn/Article/details/gt2fxtvdsht.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhengqikj.top/Article/details/gt2vnfetybq.html

C#:   (int)'A'; (char)65
来源：http://dali.zhengqikj.top/Article/details/gt2eyjfvduo.html

[A19] 交换两个变量
来源：http://dali.jqgfzy.top/Article/details/gt2ilutdwav.html

Py:   a, b = b, a
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilduzpli.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yj202588.top/Article/details/gt2hvhbuxvu.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258.top/Article/details/gt2ceynstts.html

TS:   [a, b] = [b, a];
来源：http://dali.shuidangran.top/Article/details/gt2jsgwnele.html

Java: int t = a; a = b; b = t;
来源：http://dali.c1oappe.top/Article/details/gt2xslocqey.html

Go:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gt2rnyhwoug.html

Ruby: a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gt2wpmirhiq.html

C#:   (a, b) = (b, a);
来源：http://dali.yonumen.top/Article/details/gt2kgjvihlu.html

[A20] 读取标准输入
来源：http://dali.andypj.xyz/Article/details/gt2kyjhzsch.html

Py:   name = input("请输入：")
来源：http://dali.gogol.net.cn/Article/details/gt2yiphqsam.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shzxlz.cn/Article/details/gt2wwgafgeu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangdashe.top/Article/details/gt2ruamputb.html

TS:   // Node.js：readline 模块
来源：http://dali.shzxlz.cn/Article/details/gt2mqjrezmf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jiagoushi.top/Article/details/gt2uuslvmdy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jianghu66.top/Article/details/gt2zizrixew.html

Ruby: gets.chomp
来源：http://dali.xinyue.icu/Article/details/gt2kjnouldp.html

C#:   Console.ReadLine();
来源：http://dali.yanxiufei.cn/Article/details/gt2euexzyfh.html

[A21] 保留指定小数位输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chxugjgl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.dashuyun.cn/Article/details/gt2ntbrafsm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gt2ibdjfrmf.html

JS:   (3.14159).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gt2advrbysw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gt2vsrwgqkd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gt2ukkszwkc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gt2cvihbtdo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gt2uinbxeoj.html

C#:   3.14159.ToString("F2")
来源：http://dali.haohaochexian.top/Article/details/gt2eepthdzt.html

[A22] 获取字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2jpxnzktn.html

Py:   len(s)
来源：http://dali.shuidangran.top/Article/details/gt2cdjwaczk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.bjfxy.top/Article/details/gt2mvyupobk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.kuanghao11.cn/Article/details/gt2xahrrtve.html

TS:   s.length
来源：http://dali.cashguo.top/Article/details/gt2oyireedt.html

Java: s.length()
来源：http://dali.xinyue.icu/Article/details/gt2ueqbljmf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guannengcc.top/Article/details/gt2chgokhaj.html

Ruby: s.length
来源：http://dali.c1oappe.top/Article/details/gt2ysevfwti.html

C#:   s.Length
来源：http://dali.xuanzx.com/Article/details/gt2qojvodvj.html

[A23] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2dnlxwxjb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yonumen.top/Article/details/gt2pzjeceba.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgfzy.top/Article/details/gt2kuczjmbx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwwaydfj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gt2glbsskjs.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuxming.cn/Article/details/gt2ynlzqptl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zycfv.cn/Article/details/gt2ppgqsagj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyamvhxw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.haohaochexian.top/Article/details/gt2vnxlgkfs.html

[A24] 去除首尾空白
来源：http://dali.cucudq.cn/Article/details/gt2trhmfsuy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xziqi.cn/Article/details/gt2lbldmcph.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenlongwang.top/Article/details/gt2xsbtxywc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sufxvd.cn/Article/details/gt2gcwrpzyf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cucudq.cn/Article/details/gt2tchdlbmg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.andypj.xyz/Article/details/gt2pdfwksdw.html

Go:   strings.TrimSpace(s)
来源：http://dali.hammf.cn/Article/details/gt2vhhbpwty.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.snrcjt.cn/Article/details/gt2lbxyirqt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.mhx1999.top/Article/details/gt2pcwoerxi.html

[A25] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2qrgkxlds.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndhqowww.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.daxiang520.top/Article/details/gt2beeblddr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shuidangran.top/Article/details/gt2ukoqrjwk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gt2mwhhhlfd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.haohaochexian.top/Article/details/gt2dfvqlrki.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gt2jdaaitkk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifcckjkm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxlseaeu.html

[A26] 类型转换总览
来源：http://dali.sufxvd.cn/Article/details/gt2kogdvykz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yonumen.top/Article/details/gt2eiarvhml.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzrzwhah.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlbmbgnn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangdashe.top/Article/details/gt2cnelbxrl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwnzcxrv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yvedp.cn/Article/details/gt2oixiohss.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jianghu66.top/Article/details/gt2jrdpbxud.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinqigufen.top/Article/details/gt2jrqyovzo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2nmjjrpvf.html

B. 流程控制
来源：http://dali.hysaishi.cn/Article/details/gt2lxwajsyl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfjpaoyy.html

[B01] 条件判断 if / else
来源：http://dali.yanxiufei.cn/Article/details/gt2pdfylbzt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yvedp.cn/Article/details/gt2tqgyfvgm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenzaomai.com/Article/details/gt2xixhidml.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gt2jyhbkljb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gt2zcrxjksb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gt2iogamuii.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.quarkkingdee.top/Article/details/gt2tbnrsuib.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjxlzzxc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gt2mrychiia.html

[B02] 多分支 else if / elif
来源：http://dali.zhengqikj.top/Article/details/gt2nvnqxvml.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cashguo.top/Article/details/gt2qlaxcjvu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jiagoushi.top/Article/details/gt2hqxxrcty.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gt2kiybnvhn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2eiuyfsjg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2yvwrdhee.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yangfankeji.com/Article/details/gt2wteeuaao.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cashguo.top/Article/details/gt2yhjxxodd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrdyrat.html

[B03] switch / match / case
来源：http://dali.birdmap.top/Article/details/gt2ifrhxmuj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aizwys.cn/Article/details/gt2wcvfrocu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gt2kshfyggq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gt2dzbccrfm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gt2xoinrshf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pohqnerj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yonumen.top/Article/details/gt2edzgzhqs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fengsongda.top/Article/details/gt2ybumosdk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gt2iblzqteu.html

[B04] for 计数循环
来源：http://dali.ivvv.top/Article/details/gt2zhgpjkno.html

Py:   for i in range(10): print(i)
来源：http://dali.snrcjt.cn/Article/details/gt2bidbyqva.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ivvv.top/Article/details/gt2tdnygvef.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2xwlmdknk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2enuaamhy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.tanke756.top/Article/details/gt2urfccenm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shuidangran.top/Article/details/gt2pjombwbz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zdqjudy.top/Article/details/gt2uxfphaoz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.dashuyun.cn/Article/details/gt2oagwsyiu.html

[B05] 遍历数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gt2odfefddq.html

Py:   for item in arr: print(item)
来源：http://dali.shzxlz.cn/Article/details/gt2ejdtyehy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gt2oducchfl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gt2rboswsmo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gt2zdvdakkk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2cguzrvxx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hammf.cn/Article/details/gt2rnkcidxc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ivvv.top/Article/details/gt2zepkdbbu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xziqi.cn/Article/details/gt2vajxtuaj.html

[B06] 遍历字典 / 对象
来源：http://dali.nanxuanxn.top/Article/details/gt2oaxnbteh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zdqjudy.top/Article/details/gt2razxmmkf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yvedp.cn/Article/details/gt2erwyoerp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2teipomps.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gt2nhiqmzaj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2dksfshcr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shzxlz.cn/Article/details/gt2tozcogiv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pycfn.com/Article/details/gt2litwhdcv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hysaishi.cn/Article/details/gt2vncfowxo.html

[B07] while 循环
来源：http://dali.sysykeji.top/Article/details/gt2ijaqqtat.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gt2pskcifie.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sweek.top/Article/details/gt2pyytovlg.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2gpelyfjs.html

TS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2qyigqgol.html

Java: while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdxupvei.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.mhx1999.top/Article/details/gt2dgbfdcwj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gt2rqccdrmi.html

C#:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2rcunxdcu.html

[B08] do-while（至少执行一次）
来源：http://dali.birdmap.top/Article/details/gt2jhyrlewb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jlsjyb.cn/Article/details/gt2xqlltyuz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2vfaocuar.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltsffbvq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2ykbkhagk.html

Java: do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gt2rficiwfk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tianlin.xyz/Article/details/gt2uyltidgx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ybcxt.top/Article/details/gt2oazduwao.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2boekslvx.html

[B09] break 与 continue
来源：http://dali.hammf.cn/Article/details/gt2ukrvcbvs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuxming.cn/Article/details/gt2lnpynfxe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2ewqonepm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cjbqsypk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2cjipwoqg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2vorizqwp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gt2uruhyicl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gt2lcfckjom.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2cqkxuipc.html

[B10] 遍历同时拿索引
来源：http://dali.gzhubu.top/Article/details/gt2rgpcsadz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daria6918.cn/Article/details/gt2clhhwmdp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gt2szahrwxf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqrnihyx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gt2oqzoerrc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gt2krzkjoxt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhengqikj.top/Article/details/gt2ptqnuonz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gt2daadtrbl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2lreyurgi.html

[B11] 生成数字序列 / 区间
来源：http://dali.svipenyu.cn/Article/details/gt2jziwnzis.html

Py:   list(range(0, 10, 2))
来源：http://dali.cdnleiting.top/Article/details/gt2gukjvzsb.html

PHP:  range(0, 10, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrrtxiyy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsbdsgkk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gt2fcqywzvi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cashguo.top/Article/details/gt2pxjksoge.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.kuanghao11.cn/Article/details/gt2ritjbcmu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gt2qpsltrxe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.9152youxi.cn/Article/details/gt2gqaiqhig.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2rvvcxgfn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhengqikj.top/Article/details/gt2vodvufra.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.bjfxy.top/Article/details/gt2zmmgxfhl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gt2quvttvir.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2yexojexo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gt2rsoydrzg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvydjurf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gt2otexipme.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.birdmap.top/Article/details/gt2tfajfawe.html

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugvknahg.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujowaryb.html

PHP:  is_numeric($x)
来源：http://dali.cucudq.cn/Article/details/gt2nqexrmsl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gt2cytcdres.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nyuklrem.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gt2sjdgexko.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gt2njrqgtpd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucmanqxx.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gt2bzjcaolo.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gt2kmfavezn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gzhubu.top/Article/details/gt2xekhbqad.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gt2gzekmemv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gt2ccnmwodd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2zbirjljk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aizwys.cn/Article/details/gt2irheyxii.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gt2roojuglo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gt2lwwlexwx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2gecqxsqc.html

[B15] 布尔运算与取反
来源：http://dali.zdqjudy.top/Article/details/gt2eyjbggqj.html

Py:   a and b or not c
来源：http://dali.hfpthk.cn/Article/details/gt2olebfzql.html

PHP:  $a && $b || !$c
来源：http://dali.dashuyun.cn/Article/details/gt2rqpyvsem.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2rlwuxoqc.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2zebpaqfh.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2hjieovqz.html

Go:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxtmjxfy.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2bebmueda.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2gwoghmst.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aizwys.cn/Article/details/gt2giohtgqm.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gt2wyacqqug.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gt2odunqhoq.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2thfavqpx.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqaelmbg.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gt2dasgxwac.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gt2spuzkvax.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gt2nzttexow.html

C#:   if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gt2qmsnrfbc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2tsttiiwu.html

C. 函数与作用域
来源：http://dali.sweek.top/Article/details/gt2apuvowsn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mgfexzhx.html

[C01] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gt2pggopppi.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2bsennsuj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2iwslgfgh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2xtgiuicq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2ektqfrnu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzrdcobv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndunaljb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2yehouqcl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2soupkwxz.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gt2qfncpynr.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gt2fbmjeapl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhixingplan.top/Article/details/gt2ahctigcg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2culdapzi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2noisvrgd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bulsocgp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gt2qhvhaigo.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhoulong.xyz/Article/details/gt2fcpbjwrq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cheryme.top/Article/details/gt2leawwuem.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gt2qbbdlxyc.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gt2izltmzia.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gt2hzqzyoot.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gt2wlouxzys.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gt2ftdcrvhp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2iemdujbk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpqnozz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gt2cxdmfrzo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gt2cvcsatxp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gt2tbdbubpz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenzaomai.com/Article/details/gt2jstchbac.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gt2hrcvpcpg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2clmtsgsz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gt2fzsygxqv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2bfplrssu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gt2hnwdtxtb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2hqykqmnh.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gt2djwfvwjc.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gt2oiefupph.html

Py:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2qbaywsoe.html

PHP:  return [$a, $b];
来源：http://dali.iojbl.cn/Article/details/gt2adstftpm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gt2tbjpmkjl.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gt2nrtrwgvm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gt2clwebqlj.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2fowhibko.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gt2lpajepsl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jlsjyb.cn/Article/details/gt2ajqqytld.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gt2utpvwfyl.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gt2pxpxnfda.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ehwqpu.com/Article/details/gt2ieurcjdk.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2osxofkes.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2vxrdryma.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gt2fftugoaf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shzxlz.cn/Article/details/gt2pzomsoxm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gt2nmyclvan.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmtkmmkn.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gt2hfpbbdrb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gt2pweqrpsu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gt2hyuxxlcm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gt2ehxmnque.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gt2wchbuyvm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tanke756.top/Article/details/gt2yswpbzfz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gt2cdisonvk.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenzaomai.com/Article/details/gt2gxhuaczz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gt2wqlaydfg.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gt2xueblvwz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gt2dmlbrjag.html


<!-- 参考信息 -->