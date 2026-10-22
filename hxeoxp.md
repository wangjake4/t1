代发 wailian999

Ruby: a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtyzxfrlds.html

C#:   (a, b) = (b, a);
来源：http://dali.jyoumei.cn/Article/details/gtygmmnpsr.html

[A20] 读取标准输入
来源：http://dali.havefunace.top/Article/details/gtesiewzdu.html

Py:   name = input("请输入：")
来源：http://dali.cqqwz.cn/Article/details/gtvlaiazcn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.daria6918.cn/Article/details/gtvyhjqjfd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.dianchejie.cn/Article/details/gtuavsowtu.html

TS:   // Node.js：readline 模块
来源：http://dali.cdnleiting.top/Article/details/gtaokffpbk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yvedp.cn/Article/details/gtkfkhgbmx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.sufxvd.cn/Article/details/gtdpmmgbla.html

Ruby: gets.chomp
来源：http://dali.yongpay.top/Article/details/gtzsqluldv.html

C#:   Console.ReadLine();
来源：http://dali.zhixingplan.top/Article/details/gtytvlpygc.html

[A21] 保留指定小数位输出
来源：http://dali.316326.xyz/Article/details/gtlklpoixi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jlsjyb.cn/Article/details/gtxcqrxrew.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtfwevzuad.html

JS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtojevdjel.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtwkzdmeug.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtrxdmzgzl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gtqjqzwfzi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtewrtxtwa.html

C#:   3.14159.ToString("F2")
来源：http://dali.jqgfzy.top/Article/details/gtpemgtbfp.html

[A22] 获取字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtmihbrbth.html

Py:   len(s)
来源：http://dali.yanxiufei.cn/Article/details/gtdufpkfae.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cdnleiting.top/Article/details/gtksairgob.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jianghu66.top/Article/details/gtoylzdtnh.html

TS:   s.length
来源：http://dali.bjfxy.top/Article/details/gtkjibefag.html

Java: s.length()
来源：http://dali.redwolf501.top/Article/details/gtceqwdjxl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.tian-w.cn/Article/details/gtiinrciyf.html

Ruby: s.length
来源：http://dali.zhoulong.xyz/Article/details/gtjgxgignf.html

C#:   s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtxjompbnq.html

[A23] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gtaxrryidu.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sysykeji.top/Article/details/gtyypvxflc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofwgindx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gtqgujllll.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtqnfhhitf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gtxhsyfzla.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuanzx.com/Article/details/gtignzrkfx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtovcmwrrm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hfpthk.cn/Article/details/gtgoiziavm.html

[A24] 去除首尾空白
来源：http://dali.jiagoushi.top/Article/details/gtspvwmhzf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hywenlv.cn/Article/details/gtycdigggy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttunipmqn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guowangkeji.top/Article/details/gtdfkrrswy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gtjlvajuhi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cashguo.top/Article/details/gtjksucgaw.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhoulong.xyz/Article/details/gtsmvvxcek.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.mhx1999.top/Article/details/gtrudakspv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokhbfnpm.html

[A25] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtojlgprdq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhijiandao.cn/Article/details/gtbyrepqhd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gogol.net.cn/Article/details/gtefltwtqj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtjuslbckz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpchlamj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtommsvfhx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtykvyojnm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gtptjuznzk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuanzx.com/Article/details/gtnifaerpy.html

[A26] 类型转换总览
来源：http://dali.birdmap.top/Article/details/gtokkegywz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xylfe.cn/Article/details/gtqullofyw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zycfv.cn/Article/details/gtchqeukch.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aibaodan.cn/Article/details/gtngggnjyi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhengqikj.top/Article/details/gtabpbvtey.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gtdagirjsg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.9152youxi.cn/Article/details/gtmlqeeerz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj202588.top/Article/details/gtghbjpoii.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hongshengwenyu.top/Article/details/gteczvzzdm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmxljkmqr.html

B. 流程控制
来源：http://dali.ydzc1.top/Article/details/gtmmitiglx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdiqhsatu.html

[B01] 条件判断 if / else
来源：http://dali.cashguo.top/Article/details/gtxcgakcxn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cucudq.cn/Article/details/gtejoowgyo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuxming.cn/Article/details/gtpytzqsyb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtrjpztdxr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtpvifakxm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtzyhwingk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgfzy.top/Article/details/gtmyvvmwnr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.smart0.xyz/Article/details/gtircefhsf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtpyfvqnns.html

[B02] 多分支 else if / elif
来源：http://dali.zhengqikj.top/Article/details/gtzbxmxaik.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gtmslssnvo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jlsjyb.cn/Article/details/gtewtdhmsl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtdbkwsfjs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwnerxnj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstdzhuuu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yvedp.cn/Article/details/gtpybcdave.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gaohongyu789.top/Article/details/gtwyiullps.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujeicsoy.html

[B03] switch / match / case
来源：http://dali.xinyue.icu/Article/details/gtblwlkfwd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yongpay.top/Article/details/gtwvrznssf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtyvoxufrr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtczjiipbk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtookwcflg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtekpmybvf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gtvrgxliau.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj20258.top/Article/details/gtxivuaqjj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.bjfxy.top/Article/details/gtmckgmkva.html

[B04] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gthneerhxn.html

Py:   for i in range(10): print(i)
来源：http://dali.hnqzz.top/Article/details/gteukthmej.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hfpthk.cn/Article/details/gtragtwpjh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gtnjqrvccd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hfpthk.cn/Article/details/gtcvagjovd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jianghu66.top/Article/details/gtlvqxobfq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jiagoushi.top/Article/details/gtxjfmmgvz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gtirhtunhb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.andypj.xyz/Article/details/gttvkaunub.html

[B05] 遍历数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtzglawdgp.html

Py:   for item in arr: print(item)
来源：http://dali.hnqzz.top/Article/details/gtzybiuhdn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmwrsiuy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gtfzjwdfii.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbtytzciu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ehwqpu.com/Article/details/gtwdophduf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxofbvwf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.haohaochexian.top/Article/details/gtoxrgfbii.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.kuanghao11.cn/Article/details/gtinfaqeve.html

[B06] 遍历字典 / 对象
来源：http://dali.feifeiyinyue.top/Article/details/gtkqbfmtum.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tian-w.cn/Article/details/gtbtnllrqr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gtiyyzduwv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gtxbtezgch.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtrfdibuaw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cucudq.cn/Article/details/gthkdwhrvx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.andypj.xyz/Article/details/gtpccnhmcw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhixingplan.top/Article/details/gtbuspbkbp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgouuqzd.html

[B07] while 循环
来源：http://dali.zycfv.cn/Article/details/gtidomfcog.html

Py:   while i < 10: i += 1
来源：http://dali.xuetiantiany.cn/Article/details/gtlvwjmcuw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.bjfxy.top/Article/details/gtoytycnqo.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtqsyppsac.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtgeyairsw.html

Java: while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gttoqlxcoc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ehwqpu.com/Article/details/gtgjsrhmra.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zdqjudy.top/Article/details/gtmdebbgha.html

C#:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtgwqqndpw.html

[B08] do-while（至少执行一次）
来源：http://dali.jlsjyb.cn/Article/details/gtmnhilcex.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxinkj.top/Article/details/gtgxagmkia.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yongpay.top/Article/details/gtltmtrlru.html

JS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtvooyavgc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gthzvvasfe.html

Java: do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtuuzwkbks.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gtlimcojpb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pengpengdd.cyou/Article/details/gtjyhcejpd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtigndgrol.html

[B09] break 与 continue
来源：http://dali.shuidangran.top/Article/details/gtjddbpiyg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gtxceypcfk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtsacertlh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtaaqufuba.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtxcirnfwz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxysrvajq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fzhhl.top/Article/details/gtvxjpmykv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gtnjumxacr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtrkwvpcbt.html

[B10] 遍历同时拿索引
来源：http://dali.xuetiantiany.cn/Article/details/gtuvxigqgu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gtwianxnph.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cashguo.top/Article/details/gtgjibyubp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtacwpibnq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gtsyrxgznd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cashguo.top/Article/details/gtoxrsqctw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ehwqpu.com/Article/details/gtfbwlzfoe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gtnwlhueau.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aibaodan.cn/Article/details/gtoctlyeyj.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigfzy.top/Article/details/gtmymqlwvr.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gteyymezhd.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gttfxcejrr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtllctrsad.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtxvhsdohp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gttlqewidi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jiagoushi.top/Article/details/gthnhjzbtq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gtsahezryz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sweek.top/Article/details/gtbvbfxdyg.html

[B12] 跳出多层循环
来源：http://dali.c1oappe.top/Article/details/gtlemwzpnr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkhryabu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtnncvrfqs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzrwkwiw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtzljdfpos.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtmewfxaig.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gttlndofce.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gtjwhqbuzz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daria6918.cn/Article/details/gtyhwjloeu.html

[B13] 判断是否为数字
来源：http://dali.xinyue.icu/Article/details/gtgixnektp.html

Py:   isinstance(x, (int, float))
来源：http://dali.yongpay.top/Article/details/gtxgijexrx.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gtitopepub.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gtncsefgwe.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gtragjmwkz.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjalpwjc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttivoszlo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtkbajtlax.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gtimdblxbl.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gtlfvhmdmq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pengpengdd.cyou/Article/details/gtnnxrcsxy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ybcxt.top/Article/details/gtunhznpnn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtetmcwsdi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gtduagdqel.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtgqanfrip.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxinkj.top/Article/details/gtxefmnvzg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtzqfvhaxr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtplqtpuil.html

[B15] 布尔运算与取反
来源：http://dali.hnxiangtu.top/Article/details/gttqebvueu.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyihwbves.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gtwycecahc.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtynyebajq.html

TS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtphbtampm.html

Java: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtuvvikano.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtnjgrelhu.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtanjtlpks.html

C#:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtwmlxygjr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daria6918.cn/Article/details/gtsuzsblmr.html

Py:   if not data: return
来源：http://dali.cqqwz.cn/Article/details/gtsdksvkau.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gtaxqkftic.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtmoygiaxm.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtsrnrrfii.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtsjsbxgob.html

Go:   if data == nil { return }
来源：http://dali.bjfxy.top/Article/details/gtfpnvqvlk.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gtqgucxwpp.html

C#:   if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtekqhimvp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfnyztkss.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gtlpuublhs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfzkbzgce.html

[C01] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtyxphovsx.html

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gtfxglhbgg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gthybrurwb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtfbhertcl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtgsxfcdsp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtdylyxdfo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gtreucdagf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gtkwxhcxwu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtrolcrqsn.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gttiefpqdu.html

Py:   def greet(name="World"): return name
来源：http://dali.yanxiufei.cn/Article/details/gtotbsjmmg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xinyue.icu/Article/details/gtxkwiiudq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gttyiqtfcn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqrqomoe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gtvfaotfeq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gtisomiolo.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnxiangtu.top/Article/details/gteawkyvke.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtwfhrestx.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gtluxwjjtl.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gtglfmthsy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcilqrven.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtgkekzcfl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtclrfkqjp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.smart0.xyz/Article/details/gtzhvivktf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.smart0.xyz/Article/details/gtolplayii.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gtdnvvxhmg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtrlytufmr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gtfakrnace.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gttffpgdtv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hfpthk.cn/Article/details/gtwqoqfeko.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtanxcsifa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtdwbhwkpc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cucudq.cn/Article/details/gtpiqsmqvw.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtkldiozml.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtrezhjrjb.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtrouoaydm.html

[C05] 返回多个值
来源：http://dali.sxryk.cn/Article/details/gtdwuswpra.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtvrbenqzg.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gtnlhjyskj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtjmhffnxu.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gtoukeufwa.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gthvmwzoda.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtikpbgies.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtqajaqfkj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gtazwpzmgu.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gtvhdhxjtu.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gtncsmhswo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhxscwms.html

JS:   const square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtqllwpbei.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtzetgufhh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sufxvd.cn/Article/details/gtjfqzpixq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hysaishi.cn/Article/details/gtondfteym.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gtajklaqsj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtyhagtgor.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gtkchponxr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gtsufsltho.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xinyue.icu/Article/details/gtbygphgeg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.9152youxi.cn/Article/details/gtyolqcosd.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gtbhtfzyjf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtwkuounfb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gtodjrioal.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gtodrcfvla.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxbdhvhn.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gtiylcbdwv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gtcrqmzvbg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtdqmfvcfo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtzbdyhtjb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtaxnvltsj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gtimzgwtsx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gthmfallen.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gtqkqxaspf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gttnghnzuv.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gtlkojjlxb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtcdxgipmb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gttzmcofhu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtrfmtihjg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtkkqsbejw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtgjomkgoc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gtdqksgrft.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtkqzucxpq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tanke756.top/Article/details/gthehgfuyl.html

[C10] 变量作用域
来源：http://dali.jinqigufen.top/Article/details/gtrtbrtotg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gtwqaovixa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gtuyaxoahb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gtgmfqultp.html


<!-- 参考信息 -->