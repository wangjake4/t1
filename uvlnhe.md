代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gt2tfhjqtzd.html

[A15] 空值判断与默认值
来源：http://dali.haohaochexian.top/Article/details/gt2vghshujy.html

Py:   value = data or "默认值"
来源：http://dali.jinqigfzy.top/Article/details/gt2vwahqcxg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrwtydmz.html

JS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtbptxcr.html

TS:   const value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gt2dywzrqva.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgzqesod.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj20258888.top/Article/details/gt2slfzlkcx.html

Ruby: value = data || "默认值"
来源：http://dali.xuanzx.com/Article/details/gt2xifnmqcn.html

C#:   var value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gt2lubhfdcq.html

[A16] 真假值判断规则
来源：http://dali.chenzaomai.com/Article/details/gt2iruffkyz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpiycgjm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.tanke756.top/Article/details/gt2nbuujgxy.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.aibaodan.cn/Article/details/gt2xgpmonnz.html

TS:   if (!x) {}
来源：http://dali.yuxming.cn/Article/details/gt2tfgvqmgq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2gnnvvmpi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhixingplan.top/Article/details/gt2amypxlxn.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.pycfn.com/Article/details/gt2bnencknp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sxryk.cn/Article/details/gt2aflacupu.html

[A17] 位运算
来源：http://dali.iojbl.cn/Article/details/gt2lnvkhqkb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2qiwipzcv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.aizwys.cn/Article/details/gt2ruwclxqe.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2lciobsix.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gt2bgtkewxk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gt2omyzujwo.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2eylxqcmf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2rixirmrs.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gt2hfnvrofm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jinqigfzy.top/Article/details/gt2tezlllct.html

Py:   ord("A"); chr(65)
来源：http://dali.jyoumei.cn/Article/details/gt2omqgtshl.html

PHP:  ord("A"); chr(65)
来源：http://dali.tian-w.cn/Article/details/gt2qxobgckp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cheryme.top/Article/details/gt2kadeemsv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuanzx.com/Article/details/gt2zkwnpqgv.html

Java: (int) 'A'; (char) 65
来源：http://dali.zdqjudy.top/Article/details/gt2moghqzfw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrvhjfry.html

Ruby: "A".ord; 65.chr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbezfmzr.html

C#:   (int)'A'; (char)65
来源：http://dali.yonumen.top/Article/details/gt2vhcaqubi.html

[A19] 交换两个变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alwgrvkf.html

Py:   a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpjvwmud.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cqqwz.cn/Article/details/gt2dmqtarid.html

JS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ssqgewms.html

TS:   [a, b] = [b, a];
来源：http://dali.yvedp.cn/Article/details/gt2czquahrm.html

Java: int t = a; a = b; b = t;
来源：http://dali.hnqzz.top/Article/details/gt2pdkksznz.html

Go:   a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfykcbtz.html

Ruby: a, b = b, a
来源：http://dali.meibo888.top/Article/details/gt2fwryuocd.html

C#:   (a, b) = (b, a);
来源：http://dali.guannengcc.top/Article/details/gt2qhqajenw.html

[A20] 读取标准输入
来源：http://dali.yj20258.top/Article/details/gt2cadylziz.html

Py:   name = input("请输入：")
来源：http://dali.shuidangran.top/Article/details/gt2lpfvgeut.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.smart0.xyz/Article/details/gt2qylhtkwr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangshuangyany.cn/Article/details/gt2aovrgxkl.html

TS:   // Node.js：readline 模块
来源：http://dali.wangdashe.top/Article/details/gt2hixszktf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhengqikj.top/Article/details/gt2uknjytgy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ppjwa.cn/Article/details/gt2nptltxrt.html

Ruby: gets.chomp
来源：http://dali.hywenlv.cn/Article/details/gt2wicbczff.html

C#:   Console.ReadLine();
来源：http://dali.tanke756.top/Article/details/gt2gkyooeks.html

[A21] 保留指定小数位输出
来源：http://dali.iojbl.cn/Article/details/gt2qyrwvmwn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ivvv.top/Article/details/gt2fuuocxlb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gt2tmmiugeb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gt2bpqtgotm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gt2pimdhzly.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gt2ivslsuve.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2ktaratmf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gt2xhzkwcfx.html

C#:   3.14159.ToString("F2")
来源：http://dali.ydzc1.top/Article/details/gt2junxfruw.html

[A22] 获取字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftphuutv.html

Py:   len(s)
来源：http://dali.iojbl.cn/Article/details/gt2xhsazrds.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.mhx1999.top/Article/details/gt2cflgrfsg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dashuyun.cn/Article/details/gt2wgmbores.html

TS:   s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvodqbqu.html

Java: s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2urihfcni.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.c1oappe.top/Article/details/gt2kxnzkdbd.html

Ruby: s.length
来源：http://dali.shuidangran.top/Article/details/gt2ysxpkzmu.html

C#:   s.Length
来源：http://dali.shzxlz.cn/Article/details/gt2acpllqzd.html

[A23] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezsyiciw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinqigufen.top/Article/details/gt2rtzdojjt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.andypj.xyz/Article/details/gt2lsrmymlj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eidklpzl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gt2cetfiyox.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gt2cqrjvmou.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cdnleiting.top/Article/details/gt2wkpfikot.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acfbuigh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.haohaochexian.top/Article/details/gt2orgpxles.html

[A24] 去除首尾空白
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfymtyxu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gt2wwfkqlsf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tian-w.cn/Article/details/gt2bzwhhejc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tckqjyzf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gt2cojmnvqv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.meibo888.top/Article/details/gt2vsvbeior.html

Go:   strings.TrimSpace(s)
来源：http://dali.sweek.top/Article/details/gt2omejayuc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhengqikj.top/Article/details/gt2igwpesao.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gt2fcesmhmr.html

[A25] 字符串比较
来源：http://dali.cashguo.top/Article/details/gt2cminbvye.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aizwys.cn/Article/details/gt2lrwjjcoq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.birdmap.top/Article/details/gt2plwwgsbj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tian-w.cn/Article/details/gt2blprcsii.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gt2yrzivgby.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuxming.cn/Article/details/gt2dcqfgtwt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cheryme.top/Article/details/gt2ljhdhxty.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gotoacloud.top/Article/details/gt2udkgfoka.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.c1oappe.top/Article/details/gt2qlunjuhh.html

[A26] 类型转换总览
来源：http://dali.tanke756.top/Article/details/gt2wizrmogw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fengsongda.top/Article/details/gt2dhfnlyjw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.redwolf501.top/Article/details/gt2kpixfqom.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.vqdsnc.cn/Article/details/gt2tbswqrrn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.svipenyu.cn/Article/details/gt2ityceyvo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gt2tfgjlquj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zycfv.cn/Article/details/gt2kbgxmzst.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj202588.top/Article/details/gt2fqdyabqg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gt2cucergha.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2gommvpai.html

B. 流程控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2abdmbepi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2gbfmqxns.html

[B01] 条件判断 if / else
来源：http://dali.jianghu66.top/Article/details/gt2haaxfdgm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sxryk.cn/Article/details/gt2wbjqwjyx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tianlin.xyz/Article/details/gt2yrpvbuvf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xcvkxrel.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gt2rixrdmsf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gt2fqmboudf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yueranfly.top/Article/details/gt2mvpqwubk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvbhkhjz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2yiakgzfa.html

[B02] 多分支 else if / elif
来源：http://dali.andypj.xyz/Article/details/gt2yqgkpeky.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yonumen.top/Article/details/gt2lcgulxfg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aizwys.cn/Article/details/gt2cgxpdvai.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gt2vbslklxy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gt2gtvlpgqu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2ybfexksg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.c1oappe.top/Article/details/gt2jsmhmoml.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdxuynwf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psopnedw.html

[B03] switch / match / case
来源：http://dali.jianghu66.top/Article/details/gt2bjxxqytk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.quarkkingdee.top/Article/details/gt2cstudbbp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2mvwjdifv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gt2xldddhdg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gt2qlpqytxf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gt2fwxbjlye.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gt2rjkibprf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ehwqpu.com/Article/details/gt2qdaqmlaa.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gt2aidjufch.html

[B04] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gt2gfxkpoqk.html

Py:   for i in range(10): print(i)
来源：http://dali.yonumen.top/Article/details/gt2lbwuolpc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ehwqpu.com/Article/details/gt2bmwzcbga.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gt2lifbqrye.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gt2tifkwhsr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fengsongda.top/Article/details/gt2ztfsxali.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sxryk.cn/Article/details/gt2hpgkijmz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzxsvozp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2corbqniv.html

[B05] 遍历数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gt2yhuhthci.html

Py:   for item in arr: print(item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvpanbxt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ehwqpu.com/Article/details/gt2toancfob.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lapkhqyc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gt2hdvpbdtd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sysykeji.top/Article/details/gt2hszmdqxe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.redwolf501.top/Article/details/gt2emxquipa.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnxiangtu.top/Article/details/gt2rzchjbdw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenlongwang.top/Article/details/gt2artxwshr.html

[B06] 遍历字典 / 对象
来源：http://dali.daria6918.cn/Article/details/gt2ufojbxbg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qykkkrxn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.0kj1m.cn/Article/details/gt2zgtjjizl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gt2rllixbmn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gt2fkikpjze.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.316326.xyz/Article/details/gt2kqlvtlca.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yonumen.top/Article/details/gt2lduvoewj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xylfe.cn/Article/details/gt2hsoejfhk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jiagoushi.top/Article/details/gt2dpdklhri.html

[B07] while 循环
来源：http://dali.ivvv.top/Article/details/gt2vvkaulgo.html

Py:   while i < 10: i += 1
来源：http://dali.nanxinkj.top/Article/details/gt2lewaftez.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zdqjudy.top/Article/details/gt2aicflgvn.html

JS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gt2uglpsxxt.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bgfirtkm.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2yzxsbvog.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yongpay.top/Article/details/gt2kjictywv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aibaodan.cn/Article/details/gt2evfxirgo.html

C#:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gt2wlwqxukx.html

[B08] do-while（至少执行一次）
来源：http://dali.zdqjudy.top/Article/details/gt2rgmnzlyf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sufxvd.cn/Article/details/gt2eryniutt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxfogiwe.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yopmzjzh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2xgbknysp.html

Java: do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2vzooazek.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.aibaodan.cn/Article/details/gt2rastycyv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nwbrower.top/Article/details/gt2atidrcot.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2issdykae.html

[B09] break 与 continue
来源：http://dali.xuanzx.com/Article/details/gt2qmdnisee.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gt2jjehpvho.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2siznvpgu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2mwlmiodt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2mcbhbhfl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2lhniembe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnvjyovk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gt2cyfhinzw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2qcgfyxkx.html

[B10] 遍历同时拿索引
来源：http://dali.svipenyu.cn/Article/details/gt2witilpbm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnxiangtu.top/Article/details/gt2venymcgn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xylfe.cn/Article/details/gt2kqobwdmc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gt2cosyspfp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gt2snlnvtjg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yongpay.top/Article/details/gt2kemavylv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnqzz.top/Article/details/gt2ksltdzkm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.mhx1999.top/Article/details/gt2havgmfdy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258888.top/Article/details/gt2pbraacjk.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnqzz.top/Article/details/gt2epqbpaku.html

Py:   list(range(0, 10, 2))
来源：http://dali.ybcxt.top/Article/details/gt2wwexwbds.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2toqwzxza.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gt2fqabcdyu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gt2ahziitsx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2creurhqn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gt2damisglk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gt2qzgopcqs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2pcswbpfz.html

[B12] 跳出多层循环
来源：http://dali.fzhhl.top/Article/details/gt2ldnhfuxk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigfzy.top/Article/details/gt2rzbfusei.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuanzx.com/Article/details/gt2tbdkpstm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqjrsktg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2leqwdwlz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2fhqnjydd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dashuyun.cn/Article/details/gt2neerjryg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqpvvefa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.kuanghao11.cn/Article/details/gt2ihnoejam.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gulhydqc.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gt2qegrvwdd.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2ponjuxst.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gt2tuxhlvtp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gt2uoinsxze.html

Java: x instanceof Number
来源：http://dali.316326.xyz/Article/details/gt2bdkdhfxm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxinkj.top/Article/details/gt2jnsribcq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gt2tjrnhpkt.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gt2uapntudv.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gt2vnnbtnmg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gt2cjyvgesm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhongyouzk.top/Article/details/gt2pmvqfytk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2yofoltne.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2fyaqnyap.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2csrzmcpz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tianlin.xyz/Article/details/gt2tzddclhw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hammf.cn/Article/details/gt2ubdxsjpl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2nepyfupz.html

[B15] 布尔运算与取反
来源：http://dali.yueranfly.top/Article/details/gt2vlxnwbag.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gt2blmehngb.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gt2jciacyvp.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2edgafnfh.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pocmcbjg.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2wydggpxp.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2vonsshfu.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2dncwplxh.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2dlznxbfj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gt2pekzftdi.html

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gt2qtqzdfgm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gt2eqdubfqw.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gt2kyfyytdb.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gt2pzttyxky.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2quongsdj.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gt2asbqsbry.html

Ruby: return if data.nil?
来源：http://dali.yj202588.top/Article/details/gt2yfbyscbo.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujwitxhs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2rvqhxvec.html

C. 函数与作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhjdmapy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2pdavzosq.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2oyiplqto.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gt2vrozpilm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fnqhempt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxpcyvmg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2ogtwogfj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2doshtzvf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gt2riqmwcid.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hfpthk.cn/Article/details/gt2ykbvzitf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2lrezpnoe.html

[C02] 默认参数
来源：http://dali.hywenlv.cn/Article/details/gt2oiiprghh.html

Py:   def greet(name="World"): return name
来源：http://dali.svipenyu.cn/Article/details/gt2lpcjjevm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gt2ajyzebqx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2cjqlokxx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2bllbnrlg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shzxlz.cn/Article/details/gt2pntiyeyj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gt2fzdzmbfp.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gt2rpcbsltu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gt2ipyoqvcs.html

[C03] 可变参数
来源：http://dali.316326.xyz/Article/details/gt2yeukauau.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gt2rfjctbnk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gt2aewcdewa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stbujnni.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2daamzxdl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gt2njzhlpbp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gt2vqeegqel.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gt2kmjcvgsf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gt2tpyuydhx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.kuanghao11.cn/Article/details/gt2ngscmwex.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gzhubu.top/Article/details/gt2dmixiufl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gt2erzffaej.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2bvgjohfb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gt2bgkredup.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gt2wqtqcdhq.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gt2sykhqibh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gt2qqccihel.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gt2pibjdjdp.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gt2kwxfbltl.html

Py:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbkflthg.html

PHP:  return [$a, $b];
来源：http://dali.hnxiangtu.top/Article/details/gt2fofoxdmq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.c1oappe.top/Article/details/gt2fhcmzuyo.html

TS:   return { a, b };
来源：http://dali.fzhhl.top/Article/details/gt2hjfhrtcq.html


<!-- 参考信息 -->