代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.xuanzx.com/Article/details/gthdpugjrr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gtudairmhx.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gtqdmaqxjt.html

Py:   ",".join(items)
来源：http://dali.yvedp.cn/Article/details/gtaftxfkhs.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gtuvbcyhmu.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtsbkcomdj.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtveqkstuu.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtosjfymcz.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gtgjtjzegj.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtuzohwrsj.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtjbkyeplu.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gtdgfumvjf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtlpybznlu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gtjoazbzwi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsbunose.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtkzzjehgh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtrcklltfy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gtbxvpvwtm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sufxvd.cn/Article/details/gtwjsegxzx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gtmldcejbl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gtqwwbyikd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtlzqtzajg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gtwctqkvfq.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gthuqrqhnv.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtxrpwwmfh.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtipgikxlv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtqbsczalc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtbeemhcel.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtqepinqlq.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtqxsnootx.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaltfdegd.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtxvbruawa.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtwolnhjcr.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtbdvvkvjn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtyhprsyjb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gtzoqlmyrb.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtmehxsaqm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtesxgifyu.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gtuqxmmidl.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiplaqyy.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gtjbholion.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtpsafytmt.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtvvqhzsep.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gtwrowlfqt.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gtepeaajdj.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtzfxcaill.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtnvkkmxuw.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtgxbepevn.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtulzalmxh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gtarouccak.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gteoidumdm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtvbozqtlp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtplegpydw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gtqfmsnmen.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoossqidv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gtvmwghoum.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtqbwfylxh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtpwisihkw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gtrglsqnkz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtoufefoer.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gthyltmdfv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtyuyquydh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gtpavingdj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtdnpxgdpg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtookkfjqy.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gthrklduzm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtaswhmjyz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtcjhwzrxv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtsifyekfr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gtgagvphef.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowaowqvk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.svipenyu.cn/Article/details/gtwhrdlqzc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gtllztfnoc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gtolkgmqyd.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtxkijsdcl.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258888.top/Article/details/gtskvwfkbi.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtynqynewk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtmujwwohk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtmkrrmbdk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtpfsgpubu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtoxvfugyk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtzhkfefkz.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtzoxxnyep.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gttolhmrjs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gttpbywuum.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gtyzpvhagb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdxgxgnzp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtousltgol.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtkniikeey.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gtoznwfipx.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gtsestjzsy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gtguscxxik.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gtiivmusyu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gtwypmdjkq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtriwjktie.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtkppqmini.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtpwcdpxhz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtballkksn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtmtclczwb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gtommkhall.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtimnbdvqp.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtaieqlczt.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gtcwculsgp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtcvcgkfup.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gthytzkdmg.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtynwtmvcn.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpazqvfzv.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtwdcqsfut.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gtorcjzhes.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtwnibqarp.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtdqrrbxet.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtlhkbjayd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gtsmvususi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gtbrzgbnqj.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gtzqujvdhs.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtsxwslvez.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtitkxkfmv.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gtwmefsaoa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gtxkqcsnhg.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gtwmefpgfl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtstjaoryw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtdaggjgbe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtqnyvbksp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gteigqfypb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtppecjqxh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gtfcqdefzp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtsppcfnmt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtmmfqmamd.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtfmjkrjnb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gthungsmfb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtjmfrenkj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtwzjmtqdr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjdhmqbp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtdftzvtcp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gtenpitbky.html

Ruby: s.bytesize;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtksdvevax.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtzfaonpfa.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfsbzyklq.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gtlrzorpwk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwagunwrm.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gtmsaglbzh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gtmzbxcvzw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtiigseiqa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gtozeqozbk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtqjhiknac.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtmrkisqxb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gtbvrrcrbq.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtuqycuoxt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtkpydahin.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gtptxnuzms.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtkpmqqtvl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gtgppjcmzr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtxezbpojk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxceotted.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtiiysqmgi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtaxkqpdcr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtrrkcmvkz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gtqxipbxgi.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtkgkqhubo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gtcsorikhl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtcpnvfuby.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtznyztgfm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtbxzrygdy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtixwwzgrk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gtdhafapws.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gthyrjijna.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtwehqjsve.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gteijaryni.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtomqcxitv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtqckxnumu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtbphmqlmj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtidsfgdzz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gtzvuacmwy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gthqziijwk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gtuoazytaf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gtmxhupcmy.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gtihaisjsa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtjycqwmqj.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtaqpptxsg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtnvppaypl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtkxihaeih.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtcaxlgpov.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gtdkufzdlh.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtkjhsaivc.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtdvlvnbxi.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gtcxsrxjbf.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtnoxgzlpa.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtxzswxogc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtrgxcxpkm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtomqyhjya.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtpkkbmafa.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtiiqpyajk.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtaudkaedy.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtwwvakuyb.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtjixyqjxx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtollfyhww.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gtplhukxyn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtqsnsxmfr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtjhflalay.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gtymrnwwpt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtvgmyfxrf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gtchrmtxhu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtesulxeqn.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gttprjsyhz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtpfhteotd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtnyuudbgx.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtcwbwdjpa.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtvqxowreg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtaifolvnj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtpahielyl.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gtbxjesstk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtcfklzwoc.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gtwxhdwvhw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxsirwsps.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gtdblnsygv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtayzwgkip.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gttlkenlhb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtahjbplvi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtsucnumjc.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtyyraygou.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gtinmpxeqi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtqdncrigo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtfznuqcpt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtdciniwyz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtohypkzde.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gthvconrly.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gtogfzokso.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtqbhimccm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtpaurazwx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtfszaopng.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtovgiqrrs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtefwbitng.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gtedpoxxha.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtzudzwots.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtrbaetncj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtmuovvnmj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gtdxcipmai.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtgsmfszae.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtdbgnmsne.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtnyuzufin.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gtcxhwtkns.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gtrnusdrow.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtznfiycej.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gtgypvbuis.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtfhokhlle.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gthvvrmtrz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtmdblokng.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gtdszlatuh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtovosvbke.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gtvhdlulem.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtaogblrut.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtatdakzmg.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtwphigadv.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtromnxbgi.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtuszyxmll.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gtfnquiekj.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gtxktfmnwa.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaqwllub.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtturvdwks.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtqtrmmxxq.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gtjncgttfj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtmkknxdws.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtwxiqfckn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gttyavouqe.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtycqoczzm.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtxtlivnze.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtvopqtllz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gtpptjvajh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gtkcryqzlv.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gtcltfyggp.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtzbknydva.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtrulbruks.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtutceyazt.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtdblugmsi.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtbajnnlnt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtofuopyki.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtrurstagk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gtlcgkvlrs.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtkwgiouvy.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtdctxlvpb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzhuznxzl.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtqhfgmaqe.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtxgwixcts.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatfsntxy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtmsyljraz.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtonvmmatb.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtirhbirzt.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gtpviipeix.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gtfeasixtx.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtddnfpyvr.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtydnnltgy.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtxozmgkzf.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxdplkbt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gturablych.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gtkhbsavjn.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gticfmyzhs.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtwoohvukf.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtshwynoxn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtrogictpf.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gthqeadzwr.html


<!-- 参考信息 -->