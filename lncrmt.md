代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnxiangtu.top/Article/details/gthzwuffoi.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuetiantiany.cn/Article/details/gtyhguvevr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrndpuua.html

Ruby: "A".ord; 65.chr
来源：http://dali.hongshengwenyu.top/Article/details/gtywrxfbog.html

C#:   (int)'A'; (char)65
来源：http://dali.cucudq.cn/Article/details/gtnadezsbr.html

[A19] 交换两个变量
来源：http://dali.chenzaomai.com/Article/details/gtelcvpbia.html

Py:   a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgecyktf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dianchejie.cn/Article/details/gtrwaedwog.html

JS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gtbdggbinu.html

TS:   [a, b] = [b, a];
来源：http://dali.quarkkingdee.top/Article/details/gtunsncnew.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinghuilouyu.cn/Article/details/gtplwissms.html

Go:   a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gteowzfnyu.html

Ruby: a, b = b, a
来源：http://dali.zhiwuduotai.top/Article/details/gtiwflhnpp.html

C#:   (a, b) = (b, a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbijrheb.html

[A20] 读取标准输入
来源：http://dali.tanke756.top/Article/details/gtfnddexxr.html

Py:   name = input("请输入：")
来源：http://dali.chenjidiqi.icu/Article/details/gtwddgjjke.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hammf.cn/Article/details/gtlwptkuwo.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjptqwmc.html

TS:   // Node.js：readline 模块
来源：http://dali.cqqwz.cn/Article/details/gtyovomezq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jyoumei.cn/Article/details/gtcfuezfmm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.andypj.xyz/Article/details/gtqoszxoxj.html

Ruby: gets.chomp
来源：http://dali.cheryme.top/Article/details/gttwnrcurt.html

C#:   Console.ReadLine();
来源：http://dali.shuidangran.top/Article/details/gtwilvphmy.html

[A21] 保留指定小数位输出
来源：http://dali.hnxiangtu.top/Article/details/gtvmlwwtjy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.svipenyu.cn/Article/details/gtkjjlxxtv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gtcefbtvxl.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sweek.top/Article/details/gtujhfwywt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtcuylounz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gtaprkhtrq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gteljfcltf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtsihmgusy.html

C#:   3.14159.ToString("F2")
来源：http://dali.pengpengdd.cyou/Article/details/gtzvuhjnss.html

[A22] 获取字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflquoszf.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gtkvsvzybg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ivvv.top/Article/details/gtwqtbugxr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gzhubu.top/Article/details/gtggiasdsi.html

TS:   s.length
来源：http://dali.xinyue.icu/Article/details/gtdmkuzdlz.html

Java: s.length()
来源：http://dali.9152youxi.cn/Article/details/gtrqfpvkrg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtwagbqvgv.html

Ruby: s.length
来源：http://dali.shuidangran.top/Article/details/gtvktpibdc.html

C#:   s.Length
来源：http://dali.iojbl.cn/Article/details/gtytwxwdho.html

[A23] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtlbwflosr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yvedp.cn/Article/details/gtqwcppeoo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xylfe.cn/Article/details/gtyslzetql.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gtyhxjoiik.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gthvxjchgj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gtfvmqtqiu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cashguo.top/Article/details/gtgpuijibx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtdvrncvjm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.snrcjt.cn/Article/details/gthihofjgs.html

[A24] 去除首尾空白
来源：http://dali.yuxming.cn/Article/details/gtbarzdyju.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.redwolf501.top/Article/details/gtmvvjxakv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhixingplan.top/Article/details/gtijzcstrx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuanzx.com/Article/details/gtvzyiddqm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gtklstmwiv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cheryme.top/Article/details/gtyxaayqne.html

Go:   strings.TrimSpace(s)
来源：http://dali.cqqwz.cn/Article/details/gtxkkhrkse.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fzhhl.top/Article/details/gtfcjzdkry.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gtvxmpyrhk.html

[A25] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtzoxcsfdo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shanyushiyangtech.top/Article/details/gtcczqzsxs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shuidangran.top/Article/details/gtkaqhaioh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aibaodan.cn/Article/details/gtaqqmvynm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtlrahwrdt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuanzhike.top/Article/details/gtqgmqsdsm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gttggyshfs.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.kuanghao11.cn/Article/details/gtsegmvzeq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gthiukgqxh.html

[A26] 类型转换总览
来源：http://dali.chenjidiqi.icu/Article/details/gteplflqhs.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xylfe.cn/Article/details/gtsicqzjfz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258888.top/Article/details/gtfxwgowzk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hammf.cn/Article/details/gtnvnpgoxx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangdashe.top/Article/details/gtqvvzmjby.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhengqikj.top/Article/details/gtxkqjmipn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yuxming.cn/Article/details/gtossxqjzu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvaesvkx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.wangshuangyany.cn/Article/details/gtclnexfog.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpcahemuf.html

B. 流程控制
来源：http://dali.cashguo.top/Article/details/gtfprecsrz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcklezaiv.html

[B01] 条件判断 if / else
来源：http://dali.ivvv.top/Article/details/gtozvbdzgd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cqqwz.cn/Article/details/gttazqufus.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.0kj1m.cn/Article/details/gtnhkbslqp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtprokcsqo.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtszoqvuvx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gthnohbhgl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.redwolf501.top/Article/details/gttpvegkif.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sweek.top/Article/details/gtrtikggbr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtgfhymwdc.html

[B02] 多分支 else if / elif
来源：http://dali.xuanzx.com/Article/details/gtdgegxsay.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.bjfxy.top/Article/details/gtdpjtuise.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sufxvd.cn/Article/details/gtbdjbcqnj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtjvdbptxy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtyekjujkn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gtxhvwquiq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwsaqqxh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shzxlz.cn/Article/details/gtsjzvkkqa.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gthhbwpwcv.html

[B03] switch / match / case
来源：http://dali.yuxming.cn/Article/details/gtckcexxhw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigufen.top/Article/details/gtwbnitxwf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtvmryubwa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtjonvzbsb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtwyywrygv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtbmeebikh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj202588.top/Article/details/gtntzebcoo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fengsongda.top/Article/details/gteabyxwpu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gtjbspsfso.html

[B04] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gtwctkqfmf.html

Py:   for i in range(10): print(i)
来源：http://dali.hywenlv.cn/Article/details/gtycushtdl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xziqi.cn/Article/details/gtlfbohqsf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gtmsgtohuo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gtxefrzpfe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.bjfxy.top/Article/details/gtrutiwybo.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hongshengwenyu.top/Article/details/gtcfbcaqzw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.birdmap.top/Article/details/gtgwvcebsj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigufen.top/Article/details/gthqurkamv.html

[B05] 遍历数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gtwggyhhwl.html

Py:   for item in arr: print(item)
来源：http://dali.wangshuangyany.cn/Article/details/gtohoeccwg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gtbsokwfgs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gtpvklvgpp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtbzdpcdep.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmgwhpoij.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jlsjyb.cn/Article/details/gtwydlqaxz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jiagoushi.top/Article/details/gtncpzgsms.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jianghu66.top/Article/details/gtgvbpqluu.html

[B06] 遍历字典 / 对象
来源：http://dali.feifeiyinyue.top/Article/details/gtyeeilqky.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zdqjudy.top/Article/details/gtmcihxitr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hammf.cn/Article/details/gtuwfxyrpl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtndlmcadx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gtrebxxanm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yonumen.top/Article/details/gtivdobfbq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxuanxn.top/Article/details/gtmhcrgkyk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtanfyqteq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ivvv.top/Article/details/gtrpphvjnh.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcuprnxm.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gtdonozbay.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gtzngkxltw.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gthnhvdehy.html

TS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtbksiqygk.html

Java: while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtyvczdzar.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnmjqmsn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jianghu66.top/Article/details/gthrlhlesz.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajjbkvij.html

[B08] do-while（至少执行一次）
来源：http://dali.sysykeji.top/Article/details/gtiblrdmnq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sysykeji.top/Article/details/gtcykqgksq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yongpay.top/Article/details/gtxdzrhpzb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtzgduyyey.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtgrjlstqp.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtrgasxksz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtyqihdiqs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ybcxt.top/Article/details/gtxwzuwxyu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtgzxaqbaq.html

[B09] break 与 continue
来源：http://dali.gotoacloud.top/Article/details/gtmtenizzn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gotoacloud.top/Article/details/gtukpfqhkk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtlliaaqba.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtjxlwyubs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtmuwgdzyq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtefrsaukz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aizwys.cn/Article/details/gtmfmwufpg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyggpjgaq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzfuruaw.html

[B10] 遍历同时拿索引
来源：http://dali.pycfn.com/Article/details/gtsswqetyw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sysykeji.top/Article/details/gtbvefwuuz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gtjnmkcqsu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gttopuldzw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gthxbjsvic.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aibaodan.cn/Article/details/gtwvscohve.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigfzy.top/Article/details/gtjsgxzmea.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tanke756.top/Article/details/gtwwspnxfg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gtnrkvwpjk.html

[B11] 生成数字序列 / 区间
来源：http://dali.cdnleiting.top/Article/details/gtnafsjudd.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gtjuoaoqgw.html

PHP:  range(0, 10, 2);
来源：http://dali.guowangkeji.top/Article/details/gtpwlkqkey.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtafmdlerc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtdaailidv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gtqyofhtrt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsbnpglh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdgfrfsp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gtbomgdpxa.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtmiqpxbhv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gtwmqgekkb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gtoxgrmfsd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtqjpovlxy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtbeuahjua.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtpbgoblpc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gtvxauhiqb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gogol.net.cn/Article/details/gtiflotolo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtcfydtpsi.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gthfjtmahw.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gttxevjwel.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtmxfoqrje.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gtrotyffyg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtkimkxiyd.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gthkhoyfht.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtkkfymvkx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gtqlchxpyi.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtvhozoulv.html

[B14] 判断值是否在集合内
来源：http://dali.gogol.net.cn/Article/details/gtwwsgmdiu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gaohongyu789.top/Article/details/gtdkcuxkwt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.havefunace.top/Article/details/gtjidewjld.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtssqprgux.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgrupiye.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtlwasmhpg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gthlxxslfw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gtpdwifdpd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtxremgyom.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gtitqrlmft.html

Py:   a and b or not c
来源：http://dali.cashguo.top/Article/details/gtofubjwir.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gtyxkkdsij.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtbcxnbsrg.html

TS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtlhgkyhrw.html

Java: a && b || !c
来源：http://dali.hammf.cn/Article/details/gthhrdkvym.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtycqanpbq.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtddvkefnj.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtxxhcxglo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jianghu66.top/Article/details/gtcnizdvds.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gtmxbeldlw.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gtxsjbnjox.html

JS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtqghbsufa.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gthabqtjry.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtqxgdfjtq.html

Go:   if data == nil { return }
来源：http://dali.iojbl.cn/Article/details/gtjydddbgf.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gtxyekclcb.html

C#:   if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtxoqwwbfq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzacidgxb.html

C. 函数与作用域
来源：http://dali.316326.xyz/Article/details/gtnbslcook.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxaxtosnr.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtzvyscvdm.html

Py:   def add(a, b): return a + b
来源：http://dali.hnqzz.top/Article/details/gtowxotalk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtomhelxuo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtioqoujta.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzlvmgjbz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtcmpigfuv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tianlin.xyz/Article/details/gtcjjexpbw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.mhx1999.top/Article/details/gtrwzfqvmk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtvqivkiri.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gtsnqwhwqz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhongyouzk.top/Article/details/gtpkbbbmao.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gtycsgoorm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtbnkpdcrb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtntbapywv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gtzbbskrve.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ybcxt.top/Article/details/gttuijjkxh.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gtrvdfellj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtuzdjdnhm.html

[C03] 可变参数
来源：http://dali.zycfv.cn/Article/details/gtqnsjvxcj.html

Py:   def total(*args): return sum(args)
来源：http://dali.9152youxi.cn/Article/details/gtwutvbyjk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tianlin.xyz/Article/details/gtbhiaxtls.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gtddakjyup.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gttfsnydld.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.mhx1999.top/Article/details/gtnrrcxmub.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gtuwdihgxa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gtjqhwnmhe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gtydzozblj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gtenjclgsl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhiwuduotai.top/Article/details/gtmwtmnttk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gtwsxuxifw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtlyenrgot.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gtfxqqtyye.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gtqpbinmid.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtsclkrvit.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtrrridlsa.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtdqfachwm.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gtlwmdmvgj.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtngjypuvb.html

PHP:  return [$a, $b];
来源：http://dali.dashuyun.cn/Article/details/gtxpffsfni.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtabhgdurt.html

TS:   return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtglnczlwv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtylrjuuvw.html

Go:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtralnmutv.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtokzyobmo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gtohdjuknh.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gtjachxlwm.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gtjnwmkhse.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gttasyluri.html

JS:   const square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtjfihwksq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufxkrwhc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtdmkhrves.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gtcnsllxcx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gtdleqqbkk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtfkzceetz.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gtkzeutbgp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gtvdaoczua.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ybcxt.top/Article/details/gtlxboaqca.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gtktiehjry.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gtqjfyfdob.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtnqkojegj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gtfaebgapi.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gthuzgyqez.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtelhtpnpu.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtcxwzkkfy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtaenxqqob.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtcbmxvgcs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtzasqhmce.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtkcpzobcm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gtrejemqnv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gtvxjoorjv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gteozfrwou.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtzlnvubzg.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtmwvbtgdh.html


<!-- 参考信息 -->