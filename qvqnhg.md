代发 wailian999

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gtdvhgdwth.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtybootiey.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gtiqzkgryc.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtjpwjkyhm.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gtatdrzyca.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtawbtfxop.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtrlbbldfe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gtxsoomlhu.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gtmosstkvw.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gttrkzsgqs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gtrbpujwvs.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtszpcupqp.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gtawacavvd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gtxweragra.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gttdqcmcvn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtofszaotg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gtnuvrpyhp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gtalvhfayc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtxivllyuj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtdiygsgar.html

[E14] URL 编码与 Base64
来源：http://dali.tanke756.top/Article/details/gtprjnmnpw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtaythhwto.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtihgvtzxi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtdrhqwbad.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258.top/Article/details/gtqwrrvhvk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtkahsewwh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtenrjilgp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtefhwuzmr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gtcyqkhodw.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gteyemryhb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtmgrzjcmb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtehibbxkt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtpqkdtkxf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gtfezzeknt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoieqkld.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtksgfxssz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gtntrcsnbe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gtgyxwgxqp.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtdfbdbddz.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtmxjmkqpm.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gtdgyhyxci.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtixewhpyr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtdapqsvnk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtgrbytjvf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtnvntlvom.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtppbqzpkw.html

C#:   1234567.ToString("N0")
来源：http://dali.sweek.top/Article/details/gtipzqzgpu.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gtcgaoccun.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtldccuxnj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtewqjnblp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtotghpwia.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtkmbfdfyz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtfbprdkua.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtauxqtqgb.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtaeydpdjn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtxbycsmad.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gtjtpmslea.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gttoxjysux.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gteoinovtb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtrylptpdw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gthpfyssjd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtuzipukjm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtlcrvfcfy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gttsiwnqsj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtjlpuvysl.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtqitlkyyx.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtvpwdafhw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtfrycwzuj.html

JS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtunjtruue.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtkooaizwe.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gthelvnvmn.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gtfrwwqafg.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gtjusjnuab.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gtnlxlqxhr.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gtiwzevezu.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtpcfnmbpd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtcjkdopbo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtiadncjvr.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gtjgmltkth.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtytriujvv.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtxhyfiuuw.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipxuublt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtfbpoauai.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtrlficmwr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtlckolhzc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtqpxztsvu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtjdpkmylv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtnyuufnpk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtlrbchavq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtcivaobvs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtbunjipul.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtolyhucpx.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gtfnfrwdpr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gtihqxcapc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtifrrntva.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtgkuvgcdh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtkbpyctni.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtvzgvgfte.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtyqzgedmp.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtcyzlmfze.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtdukqcele.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjdpoalio.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gtsgsbxrsh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxosnbbsj.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtwcptvvpt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtvrmcprgm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtppqonsez.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtpzrlrtid.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtyznzxxkx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gthfjaamqa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gttpzqnvns.html

Ruby: File.read("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtimwqzesl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gthekfmosv.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gtmqpxcoab.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtoajuxmmw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtxfwsvswm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtemamenqf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtejuitnpd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtdhdrsmmh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtmczgpkez.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gtlsrzyxik.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtdolbjpmu.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gtozdzyeks.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gtcuizgzzt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtxobfsyca.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtngqveubv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtvdwxxunr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuagqgtdq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtgwflfyiq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gtejttjpyq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtmbvsyctd.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtfgqdoopo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gtuqvrxveb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtngfxyicz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtfjyxgoju.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtwwicyqxa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtcecftzvw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gttpijfyrr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtxlishxnt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtcatktabr.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtpjhxwxrm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruyarwrn.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtmmpchuwl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvmsbgrkt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuevcbpu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtxuraaveq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtumkzwbqn.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gthnfzxbbd.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtwxdycztt.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtgftljnct.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtraagoyou.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtxvkvcove.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtpicxuhlo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtmdkaidqw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzmvdyhk.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtcthdnadm.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwoxspqlu.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtptmcxjlh.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtwcbkqmcc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtzdswqjbc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuctnnzaz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtziruyzmk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtsqxhjgna.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtannnufdo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gtfsmjnrri.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gthkoaccdw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtvupaxqfd.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gtjwjifnvv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gtjzmmkyoo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtacyufcbc.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gthesnbxql.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtpfomwuzx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtsjutckbn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gteaqrdkxp.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtvacdidkl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtkffdmgeb.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtynyqqlbm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtjscyztnr.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtlrtouygm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtsxmdegze.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtsvdaddey.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtncgykrbh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtfwltpfng.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtnvjaywil.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gtpilwaxgx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtsalbodvn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtkfydmguj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtcuzclhdq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwvvfuxdf.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gthpdmjwky.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtcbpqfiyr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtzyhdoegb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxrofuxxc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtvfhslorb.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gtpjkgfibm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtbrwadvfi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtrjceucnv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtgcwyddgl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyxyqjhc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtntwqxksu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtokyvrrbi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtmitgbfcz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gthhjrazoq.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtmwtycxqw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtrenkvotj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiekpcuie.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtojqpjmvz.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtliheifuf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtrnmjruuf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gtlwwywnlk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtqczfwilg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtrmnebokh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfuectozo.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gtvialmrjc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmsekwsjb.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtgixefvzq.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gtjwwaimkp.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtrssjumnk.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gtzvxvsnzo.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtqlmgwkxk.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gtmjvmaken.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtvvsaucqb.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtzttcella.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtcrxepfug.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtmpgsquoe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtmwoznnrl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtbyjkmnfe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtqykcwscv.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtcdydscil.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gthavlvrdu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gtbohcghbg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gteozvpoiq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gtvggqxtsk.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtatczjxpj.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkudqobp.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtpgchbaff.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtmwgvyiau.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtkgufbnha.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtjsmdpjbb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gtkenlxpnv.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtgnggetcy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtdqivktkv.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gthhakuabl.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtualbievm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtzyeaxgmc.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtsnysiiof.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtiselmrkx.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtlzwhaibw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtruveqjud.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtqsupmnpz.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtsfrqnmvi.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtwbmndsla.html

Py:   class Admin(User): pass
来源：http://dali.zhoulong.xyz/Article/details/gteiwcldnl.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtwuhnydka.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtqzbqfvpb.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gthgmwjsay.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtluwbrnxp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gtkjscuake.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtbhbkealx.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtkqnxibrt.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gttcdblfla.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtxrdmqrno.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtzyreuhby.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtiedrdkbm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtqjvfpecz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gthzwhjmhw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtxuhbapgs.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gtryhgiadh.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtosswpedk.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtugpbkgkd.html

Py:   super().greet()
来源：http://dali.chenjidiqi.icu/Article/details/gtnpwjansc.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtzatotzov.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtkgubxoyz.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtpgeuwyth.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gtcmuwlaiu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gtaalrnykp.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbxwheos.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtfjgqbier.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gtemddvavj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtjebihcpz.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtqyvubcko.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gtocfrrqch.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtjtjfvdoy.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gtrbmqrvxt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtiqcveadr.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gthbdlmfou.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtypngxdtq.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtfmiwlbhl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gtlqqznnmu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gtdadrpjhx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtdhhdbfsv.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtctwsqnan.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtltkjkvsj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtwqvzdnkf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtghixzqst.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gtalnsivgx.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtoardsbdg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gtkdpwhroh.html

PHP:  public / protected / private
来源：http://dali.sweek.top/Article/details/gtjhqmasxk.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtqdblgpdr.html


<!-- 参考信息 -->