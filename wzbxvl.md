代发 wailian999

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gtqkxuvwks.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtzobeagkt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtktvdxyme.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtrwaddrfu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtzzxzgrmt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtaeglvrtz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtazdlckdv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtlxoqlpyt.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtepkefdrj.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtsglinbgm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gtjfgnpavn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtgqbipgxb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gtjeujdbrw.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gtuuhbjjbg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yangfankeji.com/Article/details/gtfshlrbhq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gtaamwjmxh.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gtamfrnhgo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gttnuzxgob.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhkosfkc.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gtbhhhhzit.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gteksxfprz.html

JS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtpasfxunr.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtqiikzgzn.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gtggfmmupc.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkoxkoat.html

Ruby: items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtuzjfvcns.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtfdebcarc.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcowyodd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtrlqaltbq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gtwdyhslim.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtrzerorvy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtvkcykpki.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yvedp.cn/Article/details/gtceoutajp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gtgsdqzmte.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gteqycxcfs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtcfbevnbt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtwliwrttb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtixrelmgg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gturyyiogk.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtvljwqros.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtkwzpbsrz.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtoihpusje.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gteoyfhtrb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtyyulshfv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtmppbxooz.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtplrguszr.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtrpfkweuu.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtqhxrhrov.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtycwcbcgy.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtngjcxuts.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cashguo.top/Article/details/gtobdcbimb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtscbvsshs.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gtkczrhuop.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtbxuvdigy.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gtbofbekds.html

Py:   s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtrobghvgq.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkjlhgrs.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtxwkrklzb.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtgwsaenss.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtdrhljwvl.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gtmbjpcptk.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtkrhrfzft.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtolhowzbo.html

[E13] 逐字符遍历
来源：http://dali.zycfv.cn/Article/details/gtpcwcfkfj.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtyvuvvang.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gtwbgvpawx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtbxrkbtyg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtutbwkhid.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtxlytuqyp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtrikuzkgg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gtwowsuwly.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtazzcjvvv.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gtfnxzqpbo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gthgoyjjcl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gtynxzjoeh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gtggynifnh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hysaishi.cn/Article/details/gtdkzizjqf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtfazmvtvn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtgaofjgjn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtbwffftrs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtujwdsszn.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtgvvigcdk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gthnjrqdnc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gtjtnuthaj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtjgafehah.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gthgwppgqe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtweowoumt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gtdgqgmmmj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gtzzzlcqky.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gtyefocqed.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtkodhmdbn.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtmcrnoezf.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtrhbdnbdy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtytcsufzs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtkrqohuwc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtstrpnbdv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gtjjzwgdma.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtitamkeub.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gtdmdcwktm.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gttizipekr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gtaoneebhv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gteybrkznq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtwclfxyig.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtwxinjcso.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gtnhoinobk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtayrfkuxz.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtwuwzmnim.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnqigulc.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gtfiyilhtm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtltqfqpnv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dianchejie.cn/Article/details/gtryyurnuh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaapubpo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtuamafzko.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtinccwkfg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtutaymnyr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtrruljdny.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gtnmerugkv.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gteiaigllo.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtqutfnzbd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gtqtelzqur.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtnbiznrww.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtdopxqxis.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmvfewlq.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtzeremnuj.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtqgoftvzz.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gtekypwjcz.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gtmrtjrjew.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtvmvpdipn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gtaigiddtr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gtknbkbdqm.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtlfslmcmn.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtiastukfm.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtjuhcrbks.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gtieeouipk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xziqi.cn/Article/details/gtjcklfhvc.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gtronjmdpm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gtflyksdoj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtynptvfgj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gttfaehakp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtawpbytcp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtesivdksc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gtcwizaemt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtlxmdfhld.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtmxyrdsln.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtpdhdlrwz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtdhioljon.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gteahexduh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtkfmbtsen.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtjytfqtej.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtdwxtrkct.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtdxddktwq.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gttozrrxby.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gtyelhbmdn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcbaymepw.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gtxppbiint.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsxmlzqbd.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gtdenzrejl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsgfsbzn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtlkjhyczq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtgbawlzsn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtgwtdqanl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gteyqgbmhy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gtkuotpvdx.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtwmsxumck.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtzdexrjbx.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gtjzypfrdg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gtfykzguxa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtkxzkzuga.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtsizimsbd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtvglzzyqt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtstyffxpl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtrvqetbhh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gtxpqsrzxu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gtjwaoinkv.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gtylyoduet.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gtpgvtjvtt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtwguihwuf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gttsnapdpx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxnhdfqq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gtswzvlfob.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gtttyhfpza.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtjrcdbmwz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtuwulbets.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtuqhwtgkc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gtyzjnkukb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gtehhfmvph.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtzqqbohrt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtdxuvhmaw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gtakhcsgbq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtwtejuzqg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gtepzgqgdy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtcenilmah.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtxkkffubd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gttcojlvwl.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtffeftrjy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlnraecis.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtxjjyurcg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtluuimwtj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gtktvocwyj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtsyfgryqx.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtaqebjwoa.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtukahkiec.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtytrkfbgs.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtfxvuoagv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjwjithyi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvdgkpdvg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtvrxlczfl.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtideyuhbl.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtncyqtqdi.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtpxnwqgan.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gtfoxaztrx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtmfrmwkhq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtqdrylspz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtlyygdbyi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtffnwjzjd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gtbppzycng.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gtelnsvlbu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gtgyezqqyv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gtewfugbbd.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gtkaptschd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtuvpfoomd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtuqfjtusl.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpekogmxj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaggrlmzy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtycbdcabq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gttbkhudxt.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtuazwlyoi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcmgqprq.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtjoalggcv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtzzhzumds.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtxsmllkvz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtvjibygtk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtgqabewzj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtbvgkypex.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gtrgmvdhyy.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtylevlbmk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtonqzglpu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtmstrboze.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtdywhiwkc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtaxexkmbp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtlyelosab.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtxpefhkdl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtragoudyc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gttjkkjjrn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtbeorxvbh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwnyaehii.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtzfzyobgj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdusunlau.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gtpbxtotkd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkuchmvpd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtqgzcmrjz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtuzkfdkas.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtkkuxdumf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeypwvnd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gteseaefmp.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtelibeuuo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtsapfaepj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtqbdxigcz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gteqwbjmiy.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtrlpqrzrh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gtslaiovjx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtsowunxmm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtekblbwdy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtodphxflt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthiockauq.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gtburjhifd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtarcwzjlp.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gtpwvkndzq.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gteapycsot.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwpjxkwt.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfrswbqlx.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtzxazxbpn.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdgrfbtlz.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gtdxumbygo.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtkjnhegkd.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtdffbvzjg.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gtcyewkfbc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlomgpbu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gtcxpwkebe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gteaztymza.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxfmrwrm.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtcwmxzbmf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gtpuebulbk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtndqdymlw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtupuhnmjh.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gtedjcwfbg.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtugcxlhop.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gtslekzihw.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtgdahokfc.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtcfirvkxr.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtwiqozfum.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtgaphkzrl.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtpmhytynf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtywpegclz.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gthpctuszm.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtofozmfqv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtsailolxs.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtbzwewdon.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtryravoqr.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtmeyevztq.html


<!-- 参考信息 -->