代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtpywdqwer.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtagkinebt.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtrudizsru.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwatgzbqr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtezveuouc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gthxnyruzs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtgmstqors.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtvdxkmt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtttafrozo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.meibo888.top/Article/details/gtfzosrcbv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtgofcbvsz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtbcfhrcta.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gtgqckxkvp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtufmcfpev.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gtvdaldibg.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtltkbufus.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gthicejafe.html

Java: String.format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gteqoptuhs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtctpyhdkx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtldzsnakx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gtenysarsh.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtqkrtxfoc.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtilvhpxov.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtvbnyjfif.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtkaoflnot.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtkvavfzje.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gthxojdskr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtssdxcoud.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtaglqxxrh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtpqnezdqw.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gtewstvmzs.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtqdrtckqd.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gtymqlurky.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtlyihjpfy.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtsmxjqjds.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gthuwpevvy.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gtxxikdxmg.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtfphkwowr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gtgufgmnfz.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtmbubazzp.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gtseklbutf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtpbokuzce.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtjycqvxmj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtendfjpks.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gticlrplqn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsskrahry.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtqhizjbjf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtenbvjcdu.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gtreafhgee.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gtmmqkgmdg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtibarxwez.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gthostsgbw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gtncfuryxo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtqakfxntu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gtoelchobw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gtsaukydfz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtanhipxqb.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gttqtodbvs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gtwcxlbnnn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtcghdkzuk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtvyqrjxtu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlvlmmce.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtjijgitja.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtyeogbvpc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gtllxkpomx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gtiinldclx.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gtbfotnumd.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtypqrryxd.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gtxbjgvfam.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtidtiamgv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtsanmzkhu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtifsdszsb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtrhwkjrda.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyidyjbuc.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gtzghcpzys.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gtdriyszad.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtnetnhbjw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gthngugyzf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtdasoenoj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtjcjfuavh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gtsfidiwiz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ppjwa.cn/Article/details/gtsidnvovb.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtnxcantog.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gtoqdnqftr.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtgzsdgtww.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gtgcbfjyqn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtdafcgpfx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtjluzehyy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtgvlevuhh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtlxaplhgx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtqwjprwgv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gtejxcgjbf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtdyibecvf.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpccrghx.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gttgnkqjmj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gtfpiavori.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbrdmxrq.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtmhhststs.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gtamambmhc.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gtphaayawg.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtgjfffgbq.html

C#:   s.Split('\n')
来源：http://dali.jlsjyb.cn/Article/details/gtgtihopxn.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gtlgaienrz.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtsgksvrxc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gtzfxnmdhr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gtsdvpjglp.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gtyscsjjkd.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtihztoutx.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlnmsnmx.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtysjearkx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gtdmanxgmy.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gtqjkufivl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gtdnpxkmpi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtvecaroql.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gttesizxhx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtbydskcmy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtswjjgntk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtuouffkeq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhxxrtdx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gteepqcibj.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gtijuriaks.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gttwjhpyhb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtlzglsiqq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtgedojrnf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtjrreadzo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gtecfkwugu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gtstyyhlvl.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtuayfyyuw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtcbdakyqv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthlsvxbca.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtkivxgffy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtazyaegbc.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gtrgynfqua.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtjjqzjvjj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtevgkrcmi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gtnuliderd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtsbsqcncp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtzeovzatm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gtddjuapbt.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtphkppwrf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtdiubwnko.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtamzdwaxj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtbrddkelf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzzcujutm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtceiialum.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtwavgnivn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtvakreoih.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtucbxlsgo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtkvvwvvhr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gtobptoivh.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gtaorvldeo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtmwaoqmhg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtktbhiufa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtxkiawund.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtydtufzcs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtyvyxsjwc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gttypwowkj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gtkvlfnetd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtvjjllamg.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gtitmpczug.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxveytjh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gtgacdmemo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtvpgvwfwh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtftuaatsn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gtnfhwsdcs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtvlpjaxfy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gtwhniheik.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gtsftkngtm.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtzkjswmzg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtcapyiuag.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gthtugkkny.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtarqlqhse.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtgatorsqt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtedeunsll.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkdsqxaa.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtxygrqxey.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtpimxbmui.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtjqrkkkfc.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtfpxnlboe.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtbsfbsyki.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtvofuejks.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtuutcymeb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtuopkebsp.html

Go:   os.Remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtohcpcuae.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtaeunfqtq.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtstmcrdku.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnsunupp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtpmwdsmgy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gtobpzerbf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtoxmgvers.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtivmnsfac.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gtttlfgziw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gtetdcsghs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtzxfempoi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtyifouftm.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtctnvesvb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gticndmrmu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtiqbbrajw.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtbjiweiwc.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtepftcplk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtzcfqjbkr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtrwfahvra.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtgeoanumw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtobpbsnaf.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gtnzvksosn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtirmrfklz.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtpukpzbax.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtnbfdrzqt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtabdhdnrb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtoyaotivf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtxzultnli.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfydpwnrd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtpyactljk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gtpwqhlzbq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtlvrmyxkl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gtsrivezht.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtkxmyhsgg.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtlkncykph.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gtykshwrea.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvothjhtc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtttejcvws.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtknipldnn.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gtonhokcbg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtovvviegq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gtkglvlrbg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtcsimgkfd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gthcfpkzkw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gtmbmwgvaq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gtmartufru.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtcvibulig.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtytqvmjnr.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtpbevmhdy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gthcaqeclo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtujndhkgf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtvxqneouf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gthaxpbplz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtgnmhosgi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtjihvrjzv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqifhfgov.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gtwczhdshz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtcsulsagb.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtdppatkcu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjpqwzil.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtvzhyxgyz.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtxlsrbqro.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gttvkkxmhi.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtepfoitwv.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtnvwatkcs.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbomzuek.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtyidhzexs.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gtnysmpbkp.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtsebqvfys.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gthrgdrdmu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gtjhgvkgaj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gtssgkyycp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtgjvnwdgn.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gtmoateels.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtmzqoffzx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gtmpmsvrao.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gtctyyldct.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtezlysqff.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtuqqpnvmm.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtrkxrsgcy.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvlgsxwx.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtqkbtbgkk.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gtvwzwjdqm.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtakqrqxvu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtfmbdqirq.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtcfwzjqyl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gtpdhttxbd.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpckknjy.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtseigqslg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtjglwucco.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtlqfcbsxq.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtwokbbxax.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtepterupu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtnwlcqfpu.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtuoldfgta.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtimsahszb.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtqstopkof.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtsblksuvo.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtofbbhsup.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtdvqdcjku.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabswtmpq.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljrqavja.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gtxaeumgmp.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnmrasvn.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtdbqputcy.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gtamwkuxuo.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuyyzzxe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtmxhtfnuz.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtpksdfzvm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtxflouule.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxotofljy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtrmohsjge.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtnkvbohmr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtgujghbvw.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtlawlyoah.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtckghlpgp.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtmuivxpsm.html


<!-- 参考信息 -->