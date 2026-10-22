代发 wailian999

[A14] 注释写法
来源：http://dali.tanke756.top/Article/details/gt2nsmvbibo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jiagoushi.top/Article/details/gt2pealocmh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gt2uoefvtph.html

JS:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gt2ayvyxyeo.html

TS:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gt2qwqysrrt.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yueranfly.top/Article/details/gt2qpddsuuc.html

Go:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gt2cocxkpic.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.mhx1999.top/Article/details/gt2plrjmjca.html

C#:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gt2dzccncfa.html

[A15] 空值判断与默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2ivpwuywu.html

Py:   value = data or "默认值"
来源：http://dali.jinqigufen.top/Article/details/gt2yxypjktv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gt2mjxcupra.html

JS:   const value = data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gt2gjurzmrs.html

TS:   const value = data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gt2cacdldpp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.iojbl.cn/Article/details/gt2qoarrwpq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guannengcc.top/Article/details/gt2odecrlrn.html

Ruby: value = data || "默认值"
来源：http://dali.mhx1999.top/Article/details/gt2imyjrkls.html

C#:   var value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gt2gmoryolc.html

[A16] 真假值判断规则
来源：http://dali.wangshuangyany.cn/Article/details/gt2zoirwvzf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.vqdsnc.cn/Article/details/gt2mhquaqdm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj20258.top/Article/details/gt2yomjyodr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yangfankeji.com/Article/details/gt2fqqcymvd.html

TS:   if (!x) {}
来源：http://dali.cashguo.top/Article/details/gt2tzexfxyw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yglpzqcm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.birdmap.top/Article/details/gt2lrhlqadt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gogol.net.cn/Article/details/gt2jjutcfxw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2elgdvbot.html

[A17] 位运算
来源：http://dali.zhixingplan.top/Article/details/gt2gjnmprbf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2dsfdglhf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ybcxt.top/Article/details/gt2hrxhqvto.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2vkhnzhsh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gt2wcayjyjg.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gt2gtmiiyxd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2asifjhar.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2qpkkflfa.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyupmaw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.andypj.xyz/Article/details/gt2jdstjhby.html

Py:   ord("A"); chr(65)
来源：http://dali.daria6918.cn/Article/details/gt2wdwrespi.html

PHP:  ord("A"); chr(65)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iekdctao.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fengsongda.top/Article/details/gt2zyvlsgqy.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sflsokzr.html

Java: (int) 'A'; (char) 65
来源：http://dali.cdnleiting.top/Article/details/gt2kwgpwflp.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.kuanghao11.cn/Article/details/gt2jrmtqror.html

Ruby: "A".ord; 65.chr
来源：http://dali.hfpthk.cn/Article/details/gt2tkbuplbr.html

C#:   (int)'A'; (char)65
来源：http://dali.kuanghao11.cn/Article/details/gt2skefdooo.html

[A19] 交换两个变量
来源：http://dali.hywenlv.cn/Article/details/gt2fskpsidx.html

Py:   a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gt2zwtitlil.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yuxming.cn/Article/details/gt2yapoynhd.html

JS:   [a, b] = [b, a];
来源：http://dali.jlsjyb.cn/Article/details/gt2lcqdnbkf.html

TS:   [a, b] = [b, a];
来源：http://dali.gogol.net.cn/Article/details/gt2yyrqswyb.html

Java: int t = a; a = b; b = t;
来源：http://dali.cucudq.cn/Article/details/gt2pnhbqcjp.html

Go:   a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gt2cknoldth.html

Ruby: a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gt2vgukzqzo.html

C#:   (a, b) = (b, a);
来源：http://dali.gogol.net.cn/Article/details/gt2ovqapggu.html

[A20] 读取标准输入
来源：http://dali.sweek.top/Article/details/gt2ksdobcyr.html

Py:   name = input("请输入：")
来源：http://dali.quarkkingdee.top/Article/details/gt2ujmyeglm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shzxlz.cn/Article/details/gt2mwwakaur.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgisbjwi.html

TS:   // Node.js：readline 模块
来源：http://dali.fzhhl.top/Article/details/gt2axugtweq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jqgfzy.top/Article/details/gt2tjlpwrep.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yueranfly.top/Article/details/gt2tptvhcmr.html

Ruby: gets.chomp
来源：http://dali.zdqjudy.top/Article/details/gt2zibijvxl.html

C#:   Console.ReadLine();
来源：http://dali.tianlin.xyz/Article/details/gt2srjccxov.html

[A21] 保留指定小数位输出
来源：http://dali.zhijiandao.cn/Article/details/gt2feublwmv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhongyouzk.top/Article/details/gt2cpejwtiq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gt2bedpxmxy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gt2zsxqxgpe.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gt2hyewlcao.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gt2cuemwwkr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbnrxobq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gt2udlrkanu.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2msdwwdhs.html

[A22] 获取字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2tlesxqnf.html

Py:   len(s)
来源：http://dali.haohaochexian.top/Article/details/gt2osjmitsm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxinkj.top/Article/details/gt2webwqoxr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cqqwz.cn/Article/details/gt2ctbsfmoh.html

TS:   s.length
来源：http://dali.chenzaomai.com/Article/details/gt2zlkqqsks.html

Java: s.length()
来源：http://dali.yongpay.top/Article/details/gt2ypvlnocy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xinyue.icu/Article/details/gt2pgbscbmt.html

Ruby: s.length
来源：http://dali.hnqzz.top/Article/details/gt2eujuyzeb.html

C#:   s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxqrnyed.html

[A23] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2luwmjtyo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.quarkkingdee.top/Article/details/gt2odoyjfek.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.mhx1999.top/Article/details/gt2vqikazci.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwplltij.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gt2ybrmakda.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnqzz.top/Article/details/gt2sqbqpzuf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj20258888.top/Article/details/gt2fudbcgzk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yongpay.top/Article/details/gt2lmbqtlub.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenlongwang.top/Article/details/gt2kvoandge.html

[A24] 去除首尾空白
来源：http://dali.zhixingplan.top/Article/details/gt2lwnqubze.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zdqjudy.top/Article/details/gt2chmpdzof.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.havefunace.top/Article/details/gt2qjqoyzlx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgjgodmy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fzhhl.top/Article/details/gt2bvmlxsvs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ehwqpu.com/Article/details/gt2busmqvon.html

Go:   strings.TrimSpace(s)
来源：http://dali.daria6918.cn/Article/details/gt2mzyidhqe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yueranfly.top/Article/details/gt2nimebudo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ithfeqdh.html

[A25] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fswhzazu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xziqi.cn/Article/details/gt2xlphenwy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shzxlz.cn/Article/details/gt2ktlboklz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gt2blrljbes.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gt2uawqxbnw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cucudq.cn/Article/details/gt2imxvleqn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gt2brbkepxk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuetiantiany.cn/Article/details/gt2icuiuprr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gt2wnhvvrer.html

[A26] 类型转换总览
来源：http://dali.tanke756.top/Article/details/gt2obaxhymz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jyoumei.cn/Article/details/gt2agofsseo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sweek.top/Article/details/gt2vdwcoxqo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gt2iirpcykr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffopqyxy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrleghig.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.vqdsnc.cn/Article/details/gt2fjryeukh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ivvv.top/Article/details/gt2bszcciba.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.birdmap.top/Article/details/gt2vclnciww.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkkumcok.html

B. 流程控制
来源：http://dali.haohaochexian.top/Article/details/gt2lttiquvn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elpjnpgw.html

[B01] 条件判断 if / else
来源：http://dali.316326.xyz/Article/details/gt2hzhhypxz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnqzz.top/Article/details/gt2iisvpumd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsbheqhx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2nimblbsm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gt2ognecogu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqpxxbqs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigfzy.top/Article/details/gt2grnqudzy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zdqjudy.top/Article/details/gt2drjwvjyb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gt2prlrxaqc.html

[B02] 多分支 else if / elif
来源：http://dali.mhx1999.top/Article/details/gt2rgebqxtk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.vqdsnc.cn/Article/details/gt2rvmisely.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2idhgrwdp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2zsoizpvl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gt2dxwlcvqo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gt2zxcvmzsh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dianchejie.cn/Article/details/gt2mmviecau.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhiwuduotai.top/Article/details/gt2lspdbmwn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gt2wluafhnh.html

[B03] switch / match / case
来源：http://dali.meibo888.top/Article/details/gt2gkansqoo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hnxiangtu.top/Article/details/gt2zckbfftv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnlydfwe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gt2mdjozpqx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gt2dbldhmaw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gt2bppqsxsk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sweek.top/Article/details/gt2bpzyukym.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.daria6918.cn/Article/details/gt2atihgedu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sxryk.cn/Article/details/gt2xmfqxsed.html

[B04] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2atuxjqmk.html

Py:   for i in range(10): print(i)
来源：http://dali.aibaodan.cn/Article/details/gt2ojbnbinf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gbpqajow.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.meibo888.top/Article/details/gt2kelcrelq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2clfllwrv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cheryme.top/Article/details/gt2njuepoce.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2crcrdzrg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnqzz.top/Article/details/gt2ixhoecem.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ablkfhfj.html

[B05] 遍历数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gt2knkhjpnn.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gt2cfqssuye.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ivvv.top/Article/details/gt2pkvlvpqj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gt2mwdjmywd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sxryk.cn/Article/details/gt2gxyfyfav.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangdashe.top/Article/details/gt2hbfhawrx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.redwolf501.top/Article/details/gt2lohmgajb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jianghu66.top/Article/details/gt2ciufmqwy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmcrcmxe.html

[B06] 遍历字典 / 对象
来源：http://dali.redwolf501.top/Article/details/gt2tchecjye.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dkdbhies.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.daria6918.cn/Article/details/gt2woejango.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yueranfly.top/Article/details/gt2qxlfxppo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gt2asdaposm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbtegtxw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jiagoushi.top/Article/details/gt2jshejrfp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jlsjyb.cn/Article/details/gt2suunskfw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gt2rqqhltdn.html

[B07] while 循环
来源：http://dali.wangdashe.top/Article/details/gt2eqirigbn.html

Py:   while i < 10: i += 1
来源：http://dali.yonumen.top/Article/details/gt2nkouugvo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2ydoxyqnd.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nzlffobg.html

TS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2qucabfyf.html

Java: while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2dfkqrfpt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gt2mkrrmbmf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dashuyun.cn/Article/details/gt2ijumwhhk.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcsmizsu.html

[B08] do-while（至少执行一次）
来源：http://dali.chenlongwang.top/Article/details/gt2uqvsrwix.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.bjfxy.top/Article/details/gt2cvjlubyf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gt2mwbpqtkt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxexkhfs.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apabmfzn.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2crahuiap.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tanke756.top/Article/details/gt2hypubmtp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjfykhlb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2dwjyoxny.html

[B09] break 与 continue
来源：http://dali.yanxiufei.cn/Article/details/gt2hdzeoucr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yvedp.cn/Article/details/gt2lfjxbswe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2olaqtapy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2gmqulmhu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2igbjvbgp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2ufkehpyi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2foaqpemv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cashguo.top/Article/details/gt2jfbxllum.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2jdrudqon.html

[B10] 遍历同时拿索引
来源：http://dali.cqqwz.cn/Article/details/gt2szeewizf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvpljtmd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ymqxpgee.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqmxfukk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gt2ofqryshm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gt2ctgvfzec.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hysaishi.cn/Article/details/gt2jzdmcayg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gt2chugzgrm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gt2uujeomak.html

[B11] 生成数字序列 / 区间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbrnqyqg.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gt2homftnur.html

PHP:  range(0, 10, 2);
来源：http://dali.yangfankeji.com/Article/details/gt2szfrmbyb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gt2dfkspetm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qylptmbm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2bpqrnzpb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gt2hsadyddq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hysaishi.cn/Article/details/gt2ceqqzqvo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gt2wvmgyjsd.html

[B12] 跳出多层循环
来源：http://dali.cqqwz.cn/Article/details/gt2yksqiiik.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwhtpdzz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sxryk.cn/Article/details/gt2ehbrcxbt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gt2gvhpagzn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2zaogpogn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgckcnil.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfjzwylr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangshuangyany.cn/Article/details/gt2joifjxnc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gt2bwgaamte.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qogbneyw.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gt2wmvuqnwy.html

PHP:  is_numeric($x)
来源：http://dali.shuidangran.top/Article/details/gt2ctgxlohh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gt2nmlfjvpk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gt2edlkdrsr.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gt2umigqmtg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jianghu66.top/Article/details/gt2entbovqc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aibaodan.cn/Article/details/gt2ibnhpnda.html

C#:   x is int or double or decimal
来源：http://dali.meibo888.top/Article/details/gt2fwmyxljz.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gt2beyxsahj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gt2znsoeezn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guannengcc.top/Article/details/gt2voumhqao.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2pjxrgccl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2aqjxxhsx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2utlmpksq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangdashe.top/Article/details/gt2xxcwbibd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2ebhaiska.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2jzdrpedw.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gt2cifiebii.html

Py:   a and b or not c
来源：http://dali.jiagoushi.top/Article/details/gt2hmzewvuf.html

PHP:  $a && $b || !$c
来源：http://dali.svipenyu.cn/Article/details/gt2ciqxkuww.html

JS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2aypbmjmz.html

TS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2skkzybiv.html

Java: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wuezzoqc.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2ofvwisxi.html

Ruby: a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2aahxsnap.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyznywg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sysykeji.top/Article/details/gt2xkmujtrj.html

Py:   if not data: return
来源：http://dali.quarkkingdee.top/Article/details/gt2nizjzzvs.html

PHP:  if (!$data) { return; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jsjqhsas.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gt2ljbrktaw.html

TS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gt2wouutrgw.html

Java: if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gt2cqwdfkcn.html

Go:   if data == nil { return }
来源：http://dali.ydzc1.top/Article/details/gt2xvlpmeja.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gt2cmzbnuxo.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gt2rqowwbab.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2yerreprn.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gt2nznkhlyj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xghtrntk.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2qmdlmwzy.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqfutjmp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2npakoywm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2qklxxsod.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2qkvnzgsb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2gmdibgoc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2cwvpicen.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2woryqlns.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2kslvfpeu.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gt2vvsvbctt.html

Py:   def greet(name="World"): return name
来源：http://dali.iojbl.cn/Article/details/gt2fthfamlk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shzxlz.cn/Article/details/gt2eskseijl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2rbnjifph.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tvhujjvm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gt2zsiryfso.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gt2tvrngywg.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gt2dgnbakls.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gt2vyrlyfpm.html

[C03] 可变参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbbefgfg.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gt2oorppgjo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.redwolf501.top/Article/details/gt2xbcogoqi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2cqcftjsj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2qedirwtt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2pugdmsis.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gt2rhdpdyiv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnqzz.top/Article/details/gt2irofwhao.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gt2tvkcpvru.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gt2gdmhksbg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gt2zqfjhtpk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gt2hpkkxuav.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2flxgycll.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2koccwhuh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jlsjyb.cn/Article/details/gt2dvetczzb.html


<!-- 参考信息 -->