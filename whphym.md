代发 wailian999

Ruby: a, b = b, a
来源：http://dali.andypj.xyz/Article/details/gt2plxerpwz.html

C#:   (a, b) = (b, a);
来源：http://dali.hnxiangtu.top/Article/details/gt2otyvdexc.html

[A20] 读取标准输入
来源：http://dali.tanke756.top/Article/details/gt2usboymdc.html

Py:   name = input("请输入：")
来源：http://dali.jiagoushi.top/Article/details/gt2cpbefrej.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sweek.top/Article/details/gt2jtuylctd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gaohongyu789.top/Article/details/gt2naqhidfr.html

TS:   // Node.js：readline 模块
来源：http://dali.xuanzx.com/Article/details/gt2fvnorior.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.svipenyu.cn/Article/details/gt2wjgsdfqx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinqigfzy.top/Article/details/gt2lstejpdr.html

Ruby: gets.chomp
来源：http://dali.zycfv.cn/Article/details/gt2axxypnlt.html

C#:   Console.ReadLine();
来源：http://dali.jinqigufen.top/Article/details/gt2vtqvizqd.html

[A21] 保留指定小数位输出
来源：http://dali.hysaishi.cn/Article/details/gt2qkwfnaas.html

Py:   f"{3.14159:.2f}"
来源：http://dali.haohaochexian.top/Article/details/gt2lfirsviq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gt2nlakkjpu.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2yzwobgox.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2espovqyr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gt2emtodtim.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gt2rveupikd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxzazvhv.html

C#:   3.14159.ToString("F2")
来源：http://dali.cdnleiting.top/Article/details/gt2uzrhgigu.html

[A22] 获取字符串长度
来源：http://dali.yvedp.cn/Article/details/gt2hecunwkn.html

Py:   len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2kvlbbhas.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenzaomai.com/Article/details/gt2xaccqbld.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jiagoushi.top/Article/details/gt2gvvoivby.html

TS:   s.length
来源：http://dali.yonumen.top/Article/details/gt2blkmixkh.html

Java: s.length()
来源：http://dali.yj20258888.top/Article/details/gt2ykfjoplu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2nesbyjak.html

Ruby: s.length
来源：http://dali.yj202588.top/Article/details/gt2kqteajjn.html

C#:   s.Length
来源：http://dali.andypj.xyz/Article/details/gt2sgpnmvey.html

[A23] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2ohasnzdi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cheryme.top/Article/details/gt2gclqthzl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenzaomai.com/Article/details/gt2mhbvvece.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gt2ueulnxie.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gt2anzxdjwm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gt2phkvanmi.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.aibaodan.cn/Article/details/gt2mmwludwu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gt2ixwdebel.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gaohongyu789.top/Article/details/gt2jdjbmopl.html

[A24] 去除首尾空白
来源：http://dali.nanxinkj.top/Article/details/gt2ynbpouof.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ivvv.top/Article/details/gt2gssfyfkj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.birdmap.top/Article/details/gt2jsfjbiib.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gt2qefbsdoe.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvfjjcvn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.vqdsnc.cn/Article/details/gt2dvsdqetf.html

Go:   strings.TrimSpace(s)
来源：http://dali.sysykeji.top/Article/details/gt2iadeykkx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gotoacloud.top/Article/details/gt2iezwccti.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlhyjxpl.html

[A25] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2mpjpchdy.html

Py:   s1 == s2; s1 != s2
来源：http://dali.iojbl.cn/Article/details/gt2ayzwimgx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2jonhuexj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gt2ttiswlbg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2lixjermk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinqigufen.top/Article/details/gt2myibxrfp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gt2lpcsfpxe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilzxdbzf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yueranfly.top/Article/details/gt2euxtzflo.html

[A26] 类型转换总览
来源：http://dali.meibo888.top/Article/details/gt2xrsooedg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.smart0.xyz/Article/details/gt2dhoatzbb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.iojbl.cn/Article/details/gt2mzjdmeqy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.guowangkeji.top/Article/details/gt2ktempaej.html

TS:   Number() String() Boolean() x as number
来源：http://dali.redwolf501.top/Article/details/gt2mldrariv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gt2oebqoohn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gogol.net.cn/Article/details/gt2whlhpfof.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xylfe.cn/Article/details/gt2sajaxuqo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ivvv.top/Article/details/gt2cbfybagp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2lythnjqh.html

B. 流程控制
来源：http://dali.wangdashe.top/Article/details/gt2rrdiiwkr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ibkcicji.html

[B01] 条件判断 if / else
来源：http://dali.cheryme.top/Article/details/gt2wutndxyv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.dianchejie.cn/Article/details/gt2lfvxnbgr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yfwzwuyr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhwlbuiq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gt2zvvrlcas.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gt2btihdevs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.quarkkingdee.top/Article/details/gt2mxleurfd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nanxuanxn.top/Article/details/gt2ekstjhga.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2ufykvnke.html

[B02] 多分支 else if / elif
来源：http://dali.cheryme.top/Article/details/gt2ofllxaoe.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgfzy.top/Article/details/gt2ycblhvkm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.dianchejie.cn/Article/details/gt2mxfufbvi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gt2gqoltuaq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gt2zeutonxj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gt2aanhdmvo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daxiang520.top/Article/details/gt2vtiftguz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gt2rhibwaii.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gt2idysitws.html

[B03] switch / match / case
来源：http://dali.hysaishi.cn/Article/details/gt2ocgznanm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.smart0.xyz/Article/details/gt2dvrqpfit.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2tuejtgxt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gt2szprmbin.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ijnzksna.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gt2pxivwcne.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.mhx1999.top/Article/details/gt2ibkmvzpm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.316326.xyz/Article/details/gt2aqzsnnix.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cheryme.top/Article/details/gt2vjovyvwg.html

[B04] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gt2tjzsgqsy.html

Py:   for i in range(10): print(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybsipcxy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yangfankeji.com/Article/details/gt2sqpauank.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxuanxn.top/Article/details/gt2uvcpways.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gt2giondqdy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jyoumei.cn/Article/details/gt2wcsmxwfa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gt2jzykgltv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gt2zlfywkge.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyvyccr.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2ufyydfpw.html

Py:   for item in arr: print(item)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhjlqvbf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hysaishi.cn/Article/details/gt2vdcqupft.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gt2ftmliufk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.svipenyu.cn/Article/details/gt2dyqealnv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghbvywmd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258.top/Article/details/gt2uznargtg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnxiangtu.top/Article/details/gt2ycusgutq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gt2prfdxbfj.html

[B06] 遍历字典 / 对象
来源：http://dali.zhengqikj.top/Article/details/gt2lfnoxpet.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuxming.cn/Article/details/gt2awzrlwsx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ehwqpu.com/Article/details/gt2dflcmbzh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gt2sebqhdeu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ltgbssdo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cashguo.top/Article/details/gt2ycsshswz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lafcoclc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dashuyun.cn/Article/details/gt2dcyadimm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daxiang520.top/Article/details/gt2ubvshule.html

[B07] while 循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxgauwnp.html

Py:   while i < 10: i += 1
来源：http://dali.chenlongwang.top/Article/details/gt2pjqjfozw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aizwys.cn/Article/details/gt2kerrlwoa.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwgcmloz.html

TS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2swebhpli.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2rtuaofuw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cheryme.top/Article/details/gt2yrwhiags.html

Ruby: while i < 10; i += 1; end
来源：http://dali.haohaochexian.top/Article/details/gt2upacfbdw.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2pigqzdih.html

[B08] do-while（至少执行一次）
来源：http://dali.yangfankeji.com/Article/details/gt2ewzlwutr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gt2mudmjxzd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gt2qkipaldl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2uireosax.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2jnjvgqtj.html

Java: do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2otjlegbg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hywenlv.cn/Article/details/gt2mtvijvvi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.316326.xyz/Article/details/gt2jokddkav.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2wtvspjsg.html

[B09] break 与 continue
来源：http://dali.havefunace.top/Article/details/gt2hqasdtkb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwdsvmmk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2vhlpzrda.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ylfprews.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gt2lansgeav.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gt2qvgfcrao.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gt2jvoylhis.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuxming.cn/Article/details/gt2bzfgqkzz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2rqvdvrjp.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigufen.top/Article/details/gt2vzpeluts.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daxiang520.top/Article/details/gt2odvgywex.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gt2wlspblui.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gt2htdbtjpr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzfwpvey.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.316326.xyz/Article/details/gt2ovbifukc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnqzz.top/Article/details/gt2ycwbrste.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gt2hkygjjmm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ivvv.top/Article/details/gt2ydcclppp.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuetiantiany.cn/Article/details/gt2juuqylwq.html

Py:   list(range(0, 10, 2))
来源：http://dali.shangyingyoupin.top/Article/details/gt2hepuparv.html

PHP:  range(0, 10, 2);
来源：http://dali.birdmap.top/Article/details/gt2yjcdnpeq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gt2avgqchpl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gt2cwrslfmq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2ewvfclms.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gt2lppvhzpo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ybcxt.top/Article/details/gt2ftyyztlk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258.top/Article/details/gt2ypwrjhzw.html

[B12] 跳出多层循环
来源：http://dali.fengsongda.top/Article/details/gt2utdvripc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gt2ypnswvzh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gt2kgowbmlj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gt2oanngqeb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2ahrctngb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oikyybzl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jlsjyb.cn/Article/details/gt2bqdanlzr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nwbrower.top/Article/details/gt2dfpbnqhq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gt2vmgmbfql.html

[B13] 判断是否为数字
来源：http://dali.dianchejie.cn/Article/details/gt2xglrtpcx.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gt2jfdzvknd.html

PHP:  is_numeric($x)
来源：http://dali.wangdashe.top/Article/details/gt2ncucvgyd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gt2nxjgvkzr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gt2cdpfaivx.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whekskqg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gt2cdxhedlb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.0kj1m.cn/Article/details/gt2vftewxuv.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gt2spmtnadd.html

[B14] 判断值是否在集合内
来源：http://dali.mhx1999.top/Article/details/gt2ospjtgwr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jianghu66.top/Article/details/gt2vsvlntii.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gt2qlnhmmgu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2xtxsyatt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gt2jotlavru.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2pqyqiabz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gt2abeidbjk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dianchejie.cn/Article/details/gt2kujlqgbt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2viqhfyyj.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gt2fjuitmqa.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gt2coosohdj.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gt2bjfledem.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2xqwhbqwm.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2vaxoemlm.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfqabauc.html

Go:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2fciwjrfg.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2wigfqsci.html

C#:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2xqqmkmys.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.iojbl.cn/Article/details/gt2kepxqgqx.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhvrhjtj.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekwpfctt.html

JS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gt2hspllhke.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2kwzhmndh.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gt2ekdpweob.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gt2vfymkmlf.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgbviiiv.html

C#:   if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2giyvbxmh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2doapuubp.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gt2sgggqdov.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2jriqnuaf.html

[C01] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gt2nzsbmdkd.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2aewuebev.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2zalfdbaa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2wjhsmiti.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2zmwdnluu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2phtzwogl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gt2itmyfpvp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gt2uljhfdoj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2havbrcbt.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2neklquvo.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2toblubot.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdswmayn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2hwifueuw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovvxcgtr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gt2psxogtqn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.havefunace.top/Article/details/gt2zwmjlvax.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gt2lkobedjk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqjjlwej.html

[C03] 可变参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2amdzudyx.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gt2srunnwqi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cdnleiting.top/Article/details/gt2uumllyae.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gt2qwjfyvhc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsqvpujd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2kreqrmry.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.kuanghao11.cn/Article/details/gt2mzgawoes.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gt2dtmhqxek.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gt2rlzbucna.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gt2ehungsfx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gt2zkybqqlp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2miiplcxe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gt2gtndbiuk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sweek.top/Article/details/gt2cddnbmqb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gt2hguzfppl.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqbydlzs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gt2uscevjqi.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmpxejln.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gt2iawuxdtw.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gt2pihtnfwz.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gt2fkswlvvz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gt2wlwpequy.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gt2gaxebnav.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gt2gabqmzrr.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gt2vvpryljl.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gt2yfgtrxnn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gt2pluckjml.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gt2wwxrdqca.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gt2kluezlep.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ehwqpu.com/Article/details/gt2gaxqduwb.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gt2hduxikbg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pycfn.com/Article/details/gt2mvrwjcoo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2gsuhpvye.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gt2uhshlisr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gt2awzatdub.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omufcsrv.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gt2fqeznyue.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.9152youxi.cn/Article/details/gt2zzvyaegv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgwoblh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gt2pygulhmv.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ercyzrgg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.316326.xyz/Article/details/gt2rnxloduz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdtuivhr.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gt2pwtaezua.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jianghu66.top/Article/details/gt2csoomshd.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gt2gojgfuze.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shuidangran.top/Article/details/gt2inxkydps.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gt2dfgofzra.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xyxqcfsf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gt2deqivuyl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gt2kfmhyzto.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gt2gctwqldu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daxiang520.top/Article/details/gt2pqqxfsmb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2uepwijrk.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gt2gbvcuomc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gt2xiezylcq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gt2wlaykufc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gt2yjvuhrnm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2shosxqet.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gt2bdeyucoj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilzsghwo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gt2iouerokt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.redwolf501.top/Article/details/gt2rjyubnsy.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2iefsanic.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gt2witkeixv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gt2twgwbjof.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2gpvmlvnb.html


<!-- 参考信息 -->