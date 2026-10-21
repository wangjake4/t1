代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvwrajiw.html

Ruby: "Hello, #{name}!"
来源：http://dali.hnxiangtu.top/Article/details/gtqthprzng.html

C#:   $"Hello, {name}!"
来源：http://dali.ivvv.top/Article/details/gtdpgcldzc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.birdmap.top/Article/details/gtmdxebphc.html

Py:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtpsrjdamo.html

PHP:  "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtvtnlcolc.html

JS:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtveexsicy.html

TS:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtaxxbdlpl.html

Java: "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtbgmilxuf.html

Go:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtvlrqcjur.html

Ruby: "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywbbjxpy.html

C#:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtcbqfmdse.html

[A14] 注释写法
来源：http://dali.guannengcc.top/Article/details/gttnqgnrxc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhiwuduotai.top/Article/details/gtdkoiftwc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gtbykbhdvx.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gtywmhcimh.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gtesgtrytb.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yanxiufei.cn/Article/details/gtwqvblveh.html

Go:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtxumarmub.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgufenzy.top/Article/details/gtbetudbvu.html

C#:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gthnntqetl.html

[A15] 空值判断与默认值
来源：http://dali.ehwqpu.com/Article/details/gtibvnsogc.html

Py:   value = data or "默认值"
来源：http://dali.yanxiufei.cn/Article/details/gtcrdfyape.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqmrrutt.html

JS:   const value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtsibkmzhn.html

TS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gtturjlakm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.wangshuangyany.cn/Article/details/gtufbeuajg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.iojbl.cn/Article/details/gtgnpahicg.html

Ruby: value = data || "默认值"
来源：http://dali.aibaodan.cn/Article/details/gtpokjqndt.html

C#:   var value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gtvxhfthwu.html

[A16] 真假值判断规则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwwgaijn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gotoacloud.top/Article/details/gtgxuzxign.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.quarkkingdee.top/Article/details/gtgmfkcfqu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yonumen.top/Article/details/gtgeoedbrk.html

TS:   if (!x) {}
来源：http://dali.snrcjt.cn/Article/details/gteluirdys.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xinyue.icu/Article/details/gtdlbfdoyd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cdnleiting.top/Article/details/gtpqvgvtsh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangdashe.top/Article/details/gtopnvzidx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtwdpmezqy.html

[A17] 位运算
来源：http://dali.cheryme.top/Article/details/gtbzfhoyjf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtvxpyfiha.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtfyiiuhct.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtfhvmqmit.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtsndbezki.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtpvfiifcl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtjfdtggjh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtlgnipofy.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtwbfqcxpr.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jlsjyb.cn/Article/details/gtgbnekbfq.html

Py:   ord("A"); chr(65)
来源：http://dali.yj20258.top/Article/details/gtoqkbkjau.html

PHP:  ord("A"); chr(65)
来源：http://dali.nanxinkj.top/Article/details/gtescbbvnk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtonhggntv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jqgfzy.top/Article/details/gttnixnsjv.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gtlgfamubd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcidzerjp.html

Ruby: "A".ord; 65.chr
来源：http://dali.9152youxi.cn/Article/details/gtcbvkrxgp.html

C#:   (int)'A'; (char)65
来源：http://dali.chenlongwang.top/Article/details/gtfyaccrwg.html

[A19] 交换两个变量
来源：http://dali.birdmap.top/Article/details/gtklpnjhih.html

Py:   a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gtrysnswdd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.svipenyu.cn/Article/details/gtqsfnoeua.html

JS:   [a, b] = [b, a];
来源：http://dali.ivvv.top/Article/details/gtxoclodgn.html

TS:   [a, b] = [b, a];
来源：http://dali.tianlin.xyz/Article/details/gtnecpvaad.html

Java: int t = a; a = b; b = t;
来源：http://dali.nwbrower.top/Article/details/gtrvvcceib.html

Go:   a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gtbewjkaiy.html

Ruby: a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqvexxfh.html

C#:   (a, b) = (b, a);
来源：http://dali.zhixingplan.top/Article/details/gtzrknzfhr.html

[A20] 读取标准输入
来源：http://dali.tianlin.xyz/Article/details/gtgcqyimpu.html

Py:   name = input("请输入：")
来源：http://dali.jqgufenzy.top/Article/details/gttaeudpvd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.chenjidiqi.icu/Article/details/gtwrsalntp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.guowangkeji.top/Article/details/gtjtwohfdx.html

TS:   // Node.js：readline 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtywgsqtkn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hywenlv.cn/Article/details/gtvsmwumxs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xinyue.icu/Article/details/gtpqkbcgsp.html

Ruby: gets.chomp
来源：http://dali.aizwys.cn/Article/details/gtjepriwdr.html

C#:   Console.ReadLine();
来源：http://dali.0kj1m.cn/Article/details/gtcvbkjbhk.html

[A21] 保留指定小数位输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxapywdd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.wangdashe.top/Article/details/gtvxhpqpyn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtwbkihupa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtkrxxwwab.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gteggvhfcd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtsemcdayc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gtboxmmqew.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gtthvewmht.html

C#:   3.14159.ToString("F2")
来源：http://dali.gaohongyu789.top/Article/details/gtokbesmsr.html

[A22] 获取字符串长度
来源：http://dali.ppjwa.cn/Article/details/gthjrcunqn.html

Py:   len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjtmgikvh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sweek.top/Article/details/gtjmihpkdf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbczyobyq.html

TS:   s.length
来源：http://dali.cqqwz.cn/Article/details/gtvclhkwfa.html

Java: s.length()
来源：http://dali.shuidangran.top/Article/details/gtgggjocpm.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dashuyun.cn/Article/details/gtznovpkyk.html

Ruby: s.length
来源：http://dali.xinyue.icu/Article/details/gtskpfzcqp.html

C#:   s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtabcpoxix.html

[A23] 大小写转换
来源：http://dali.cashguo.top/Article/details/gthctjktyb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jiagoushi.top/Article/details/gtutkyopxd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zycfv.cn/Article/details/gttjygkjez.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtqzmjzvhb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gtharrtmso.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtkyrelbqg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuanzx.com/Article/details/gtkyjokgmr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtsxkqsrzk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xinyue.icu/Article/details/gtxmhlbvjt.html

[A24] 去除首尾空白
来源：http://dali.hnqzz.top/Article/details/gthdxxqcro.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.svipenyu.cn/Article/details/gtugpqhbzh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gtqpzvzjrq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmskrgkkb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gtxgedsxhg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nwbrower.top/Article/details/gtjcdbtxxv.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj20258888.top/Article/details/gtbobqqxtu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.haohaochexian.top/Article/details/gtzvbfuvik.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtjvxlwdjv.html

[A25] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvrghskn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gtqlfbrtlj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xziqi.cn/Article/details/gtmqptqnno.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zycfv.cn/Article/details/gtuyuzhofh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.bjfxy.top/Article/details/gtrolpqauh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangdashe.top/Article/details/gttvpkqybm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtwednhwim.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cucudq.cn/Article/details/gttkddmoum.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gtgnnklryb.html

[A26] 类型转换总览
来源：http://dali.ybcxt.top/Article/details/gtlxxvmnsf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shangyingyoupin.top/Article/details/gtbdyhngjg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.birdmap.top/Article/details/gtczgaxtzm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.9152youxi.cn/Article/details/gtnjjdmbtf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hywenlv.cn/Article/details/gtwngjqgww.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtngrnmors.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfguzqdq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.daria6918.cn/Article/details/gtxoswwpzi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gticvjlmng.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpcyqqdwz.html

B. 流程控制
来源：http://dali.hysaishi.cn/Article/details/gttqaeqbfg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtnbdemebp.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gtlssstqmh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guannengcc.top/Article/details/gtklvdrgnb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.wangdashe.top/Article/details/gtairwvdnf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gttzurvhpq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtkzopyvbs.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtfrwhjttp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gttdixotwk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuxming.cn/Article/details/gtsnxxvewr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtcargxvsc.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gtkqnvtarp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenzaomai.com/Article/details/gthwhbmgho.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gaohongyu789.top/Article/details/gtdmfrwicd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gtzvsfnpso.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtenkzpvzb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtsxrgupwk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gttdbavair.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtytkcctlb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlbabrpa.html

[B03] switch / match / case
来源：http://dali.hywenlv.cn/Article/details/gtlahgeqvp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenjidiqi.icu/Article/details/gtlaouygdo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtqrixpeaz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtawsmkodc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtpswqgbqj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtagyssyhv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.andypj.xyz/Article/details/gtkwlhnfoe.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tianlin.xyz/Article/details/gthdikyhid.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sysykeji.top/Article/details/gtlhydpsfw.html

[B04] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtwisjhdxr.html

Py:   for i in range(10): print(i)
来源：http://dali.yueranfly.top/Article/details/gtajpfkxgo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinqigufen.top/Article/details/gtdxnomhiq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gotoacloud.top/Article/details/gtaqocjqzg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gtybpykmvv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhixingplan.top/Article/details/gthwacgigu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dashuyun.cn/Article/details/gtxcnslzrt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daria6918.cn/Article/details/gtwwrxejok.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.haohaochexian.top/Article/details/gtnejdnwms.html

[B05] 遍历数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtxszvrjde.html

Py:   for item in arr: print(item)
来源：http://dali.shuidangran.top/Article/details/gtwnuwwlxc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cucudq.cn/Article/details/gtkealclvy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtlbuzriqy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guowangkeji.top/Article/details/gtodylcfha.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ehwqpu.com/Article/details/gtcrjalgbm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cheryme.top/Article/details/gtqkygvudu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.0kj1m.cn/Article/details/gtrnxjrvhg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tanke756.top/Article/details/gtudidtnxo.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258888.top/Article/details/gtsqvuxreo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daria6918.cn/Article/details/gtorvlhckn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ehwqpu.com/Article/details/gtdueqwsfm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gtuqullxtv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtzeeerkpy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.smart0.xyz/Article/details/gtbxjliesz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cheryme.top/Article/details/gtjdkiwyam.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhixingplan.top/Article/details/gtaplbxaxx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvmoqxmx.html

[B07] while 循环
来源：http://dali.yongpay.top/Article/details/gtwwmgagzw.html

Py:   while i < 10: i += 1
来源：http://dali.xylfe.cn/Article/details/gtqwyvyehs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsvcgeavn.html

JS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtfpeghtjt.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtneodsdmo.html

Java: while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtpdvnzesl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258.top/Article/details/gtvqtqnqau.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gtdvyhyzzu.html

C#:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtyexlqflk.html

[B08] do-while（至少执行一次）
来源：http://dali.jinghuilouyu.cn/Article/details/gtphjhyrsu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cashguo.top/Article/details/gthzluzpzt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtglvukmgh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtovrxpttm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtfwadtorc.html

Java: do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtxzkmyiwb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cucudq.cn/Article/details/gtadrugnip.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gtocfqctwc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtdyremfth.html

[B09] break 与 continue
来源：http://dali.yj20258.top/Article/details/gtevmuleqv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gtsflstcfh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvfxooow.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gttluyzjlx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtachveupm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtzmugzfnm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gtatarriro.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxinkj.top/Article/details/gtsewnlddj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtyaajedkw.html

[B10] 遍历同时拿索引
来源：http://dali.yueranfly.top/Article/details/gtgbxoaxpb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gtkvyvnzhg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gtjniwgrlk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gtxttfbcuq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsomiwbvt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258.top/Article/details/gtioiljdvk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuanzhike.top/Article/details/gtdnmdoack.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ybcxt.top/Article/details/gtschgyepj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.kuanghao11.cn/Article/details/gtngvseikm.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gtypxttlij.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gtoqeauzbg.html

PHP:  range(0, 10, 2);
来源：http://dali.wangdashe.top/Article/details/gtnsxunvar.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gtstscbmfc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtizwavikq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nwbrower.top/Article/details/gtqbqoypdd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gtoturlwss.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtlvdcbqwz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gtspzmzsew.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gttahzogoq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.snrcjt.cn/Article/details/gtrllwwihf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gtbfrabyft.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtbpfbtjhx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtdfamoxjh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtfynoaoue.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gtepzpsvmd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.havefunace.top/Article/details/gtjjvfinia.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhengqikj.top/Article/details/gtxekpyxbh.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gtxtkkwhkj.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258.top/Article/details/gtmgwrstnh.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gtfyooheex.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gtoyqgddjv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtrjxmlsnm.html

Java: x instanceof Number
来源：http://dali.hnxiangtu.top/Article/details/gtshysjput.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jiagoushi.top/Article/details/gtklmzdocq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gthpscqcaf.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gtjneqnfgy.html

[B14] 判断值是否在集合内
来源：http://dali.xuanzx.com/Article/details/gtsrldzamu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.meibo888.top/Article/details/gtjglgwcba.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gtqxefrquk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtckrwqeas.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtlzjzhrly.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gtqowqkaen.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtkhxxjugs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yueranfly.top/Article/details/gtnnrhlubt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtyvykgvaz.html

[B15] 布尔运算与取反
来源：http://dali.gotoacloud.top/Article/details/gtthheqzjz.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gthnyzpjkd.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gtghsemhla.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtzooobdep.html

TS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtkhxmahst.html

Java: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gttnnipztl.html

Go:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtsuylruww.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtmsvvrziv.html

C#:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtuvgyggnd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shuidangran.top/Article/details/gtdwfxgctd.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gtfthlihwv.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gtrepizczn.html

JS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gtqpupffqi.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtzmqtolpc.html

Java: if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gtklwsbdwj.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gtluolqsxn.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gtdafqgcwo.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtbtnmyzye.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtybkypmac.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gtzcxqzxhg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfzejtdkp.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtafhileyb.html

Py:   def add(a, b): return a + b
来源：http://dali.cqqwz.cn/Article/details/gtgeuvoily.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtrhywpdoy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtqbypvqoc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtkctshbkp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtxlaimvei.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sxryk.cn/Article/details/gtumrytoex.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gtwivqhqrs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtsvhmwovy.html

[C02] 默认参数
来源：http://dali.jyoumei.cn/Article/details/gtkttdalij.html

Py:   def greet(name="World"): return name
来源：http://dali.wangshuangyany.cn/Article/details/gtqnvkgpvc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gtqzefmzoa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtpkopfmcb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtcmwxjzjj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gtakyvgulg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gtmwomidtd.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtrmhqhbnp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gtovsdxcyx.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gtwcbpniod.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gtersodfet.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gthuxiikjk.html


<!-- 参考信息 -->