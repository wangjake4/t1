代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gtqwhcgddx.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtesubschc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjlmecrj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zdqjudy.top/Article/details/gtcjhnfokz.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gtrfixecyi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gogol.net.cn/Article/details/gtnfotxhhx.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gtuyeecqdi.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gthwwfuxuq.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtfzeqehzi.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtnfiechru.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtklswatqg.html

Java: String.join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbehstlki.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gtltujdchs.html

Ruby: items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtnadjetvo.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtsjyxkeyz.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtvfehigdo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtmeychzzv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gtdhilgjzw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtfxqgpvea.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtfbfdrllt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosdaaqnm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtklcggaky.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gtbrwxrujb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtmmkpzhlt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gtcnhxekjx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtgggftnft.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gtcbtmefad.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtgrcvwtpj.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtjahqdnkl.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtbedvdtig.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtkprjhbog.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtftqadgmq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtbwkkmajs.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gtyfmdyfyb.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtcdsmyvgw.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtugbovqdn.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtjlwxdofu.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtwpehrrpm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gttrmzopsf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtnmglerqw.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtrynghuaw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gttriqsxer.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvhpxqkh.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtdyqqmqpw.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gttydngxlj.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtxywxjqgf.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtvivhbcuq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gtvuobobbz.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlvarskb.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtpnhrsdxp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gtgezqtist.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtcymvegbz.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtqmtsaoox.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gtgiuywsce.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtoypqynyi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtmvvzkasb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtmcqvxtqi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtypftcyan.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtypdfiejr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtxmmcpfrs.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gtcqkozewy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtnuprxpgq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtskzknvjy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gthvmqverz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gthyisnpmv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtbssrzxjh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtxbnxsatd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gtqrztrfqx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gthdldgxfu.html

[E15] HTML 转义 / 反转义
来源：http://dali.xziqi.cn/Article/details/gtmzxebrxk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtraunczgz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fengsongda.top/Article/details/gtotwzuict.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzgfsprm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gtvrhakynv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtcpeiubiz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gtwesecsur.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gtyguggzrb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtqaacflyu.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtjaijxwtq.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gtkqfavwex.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvytsjlg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtduueoifl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtsncjkikz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gtexpavvfb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gtfawcvffc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gthicfbcgw.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtyapqpptj.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gtqsfblpbb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gttpyewrfu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtiuoxrylj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtcvlhmevd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtxjzlocrd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkjvkrai.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtybagoiji.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gtavlsjiwz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gtcagrrnod.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtcjhvhhxo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtfqllczru.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gttmtkcfjw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtvieltuyu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtkdqlemgr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtwpfrchpb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtesawftvr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gtmplnbush.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtfdacxgaa.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtvvebhlcg.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtebdfbgdj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtaochukuy.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtomdquyea.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtwytfxque.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gtoqyocwoy.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gtqstnyckh.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtbthxbrql.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gtfjemrbqb.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gtxbofdcxx.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gtupmhekyf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gtufvonczm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtorpvijyc.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gtkcoxqymw.html

Java: if (s.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtwpsiufzh.html

Go:   if s == "" {}
来源：http://dali.ybcxt.top/Article/details/gtwknjflcm.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtpbiwjktz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtriistfbo.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gteuwlkvyg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtbhrvdvtj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtfmxzbwba.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtmagszxdc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtztvzeeie.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtqbkgyzgb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gttbilfcoc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gttqrmkdfd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtzkmrinss.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gtwgflnhiv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtmljwlesj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gthrcxtpci.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtpcgjzujj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtmomdphmq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeenuopl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yanxiufei.cn/Article/details/gtxmuuvbld.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gteilovugn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtxeizzjml.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtytfmpnvo.html

F. 文件与目录
来源：http://dali.xylfe.cn/Article/details/gtypcopdes.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtthoruwos.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtimvcrsav.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gttpipxvgz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtotdmrnmj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtxpwdktil.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtmgitjqal.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtwfvplqoz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbfsdzpf.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtikudrvlx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtjoyayprp.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gtoaygcqek.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gtcvzmbglj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gthtmkpufe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtylikezdo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtfchmxqgp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtywpfsvnq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrtxeovf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gtgutngqej.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gteuikqsnz.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtrhgvltdk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gtcsjdraiw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtvtaoetuk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtnhewacbe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlnzzqsn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtqiizeyre.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gtkijccmfx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtrzwhjzcv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtiojzrhwj.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gthanqyznz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtxiutmvbh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhmitegr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtcgpdzekw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtyvxpinzf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gtqieauiyp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gthlexvoqk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtavufblul.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtdqreoumu.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gtprjhadnx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtnnkkqhfy.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtemccavbl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqanamxgq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtwhjljnax.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtijptcbgc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjchjsdx.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtlucpkjkd.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjpqjxdxe.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gtcjbcobga.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gteadewbgy.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmaoqkya.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwxomnuxy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtdirjhhrf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtvcjvfcpc.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtsxneftqg.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gtvwjhgaot.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtkmvqwkim.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gtbzlnyydp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzamnvdiu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtbkdyznty.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gttlprygws.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbipknbju.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtnsuonbew.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gtmjifhoan.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtcvpibeho.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gtdqrzfdfw.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtkddnhpxs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gtkbeebjyt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gttqxbkkwm.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtfvnrintm.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtohxseisz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtzsdeqqtn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtniomcgwy.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtlohckbfu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gtfsfyengq.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gtkrmgmhof.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtbgphkchc.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtfugqelzq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtfiansjee.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gthwdbldes.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtftmpetxy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacxokibj.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtgpeggypx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebmmpbag.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gtjnwwdphu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtryktghyy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtgxnstfdv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gteqgjbvxn.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtdraqchuq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtujdosusz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtfebzjxop.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgfnkqvlo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtearuvnvo.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtipeqytiy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtrtrzdfaz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gtqivhvydv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtkjcpnrzm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtddrrzzwi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtodnhzvlm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtkeyrctjv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtcxmylnfm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtezmlexnu.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gteiqfaksu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtlsqwugts.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtfwjsmkbi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gtqbvuvdlz.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gtikvgbbys.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtnybitqyh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gtrpaqceby.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gtyslavwtf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtrwjdmoyf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfsuewpqj.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gtwusdbljz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdsbpihrh.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtkrpaaths.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtpqmnhwbo.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gtiidbhuom.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtalylhusi.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gtswjsrtua.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwnwuzas.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtmpnfxotj.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtbgnjayas.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtcbgmqcpd.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtptoivdsk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtsjakqzxm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtelpdkmiz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtnnjwntpg.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtjmcxxwxk.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtrzojonwe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gtvatikxbt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gtshjzriad.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuprqfhxq.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtuvpcznix.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtnedljzer.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gteetaeskl.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsezamtia.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtimsaktdw.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtzpaspfcv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gtpquqoskd.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtmjbjqkdf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtmhedkfuk.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtcpnheluz.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtkmgcnvwx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdaixhliy.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtsdjhaftl.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtywkzculi.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtvvtjesea.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtgnncbunt.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtcvablcsk.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtsquanojd.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtffnqogsf.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtxgcgzmuy.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gthkdhicog.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtqezwbpgd.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gthjhxoqhb.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtkazlceap.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtwguniyjz.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gtdeeikckb.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gthiczyslo.html


<!-- 参考信息 -->