代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtdjfxzmoo.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gtwknzvrkn.html

Py:   s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtetkhgqxw.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtxlorabqd.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtxykvyiub.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtnkgsqhrf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkivrvpxs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtdtsvvosx.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtwcscxctz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtxyiyaele.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gtczwavltx.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlhshtmi.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gtonyktxjo.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gteuelnrru.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtdqrwsgzy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtanagtysn.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gtlwaqucwk.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtuzozviby.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gthxjqrdaj.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gttgsprjje.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gttgztqart.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gturbtdwet.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcqrexwx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtcpmstmdh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtqopwqahi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gtdfynblvy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdkcqeab.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtwypwcyep.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gtnhdblthm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtdaafecfz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtjwbiqhqc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtrkgguuox.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gtdjronhyy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gtpxupuwmx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtjcoyinjd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtsvhzkidj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gtibiopuov.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gtjiswxhfn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgzjovvv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtyaahhqar.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteemxsybf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gtlsohbtgu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gthxilnsly.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gtyynkliml.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gtmcnkrvyd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gtvzixzite.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gtkcbavfmj.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gtuwbqmtqo.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gtuhaiquyb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtkjbfhuxh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuholdcel.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtxkwljmcv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gtiacsajtp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.316326.xyz/Article/details/gtyefdifyu.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gtdvjfjymi.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpmrlyjl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gtooseryyb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gtarwizbcv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtdaezkckx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtisbthjgo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gtxdnictse.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtedpnlkgo.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gtricjquvo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gtnaxehwcn.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtbjlimeyl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtowpzfleu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtauefydke.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtgcqgmnub.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtapunhpll.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtzxjipuan.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtvsduurme.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gttooiagdi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gtztnjfhir.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtfdvupkwc.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gtbtyeoorw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtutdfgiwo.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtucypnizp.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gthoyrwudj.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtqlbpgthz.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtpnchznly.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gtcnfbhism.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gtijjmabtv.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtyccsnmod.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gttagdmeqd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gtfpgmrbog.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gtyxkywgcl.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtavusxaqk.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtoekairvl.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gtplrjrxpg.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtpnyuzorf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbtozpxuc.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gtacbubhfc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtqkmclryi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtabclzkvz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtllmbzkbj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtesxinjcw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtglnzfgom.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtikvxgqds.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtkyhypecl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtcnnuilgr.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtialuriww.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gtrutylqtp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtpwadyaso.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtccwqpoaq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtrqcwjzlr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvyvrjdw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtkwvzeqvj.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtjkgzufpm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gtyohzojpb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtoecnypip.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtseoilknb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtiikskrzm.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gtxjdagamn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nwbrower.top/Article/details/gtenylawal.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdccqiemg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gtdbdkfjso.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtoopltnlk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtgizynzun.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtjpeeezta.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtonpjkbdn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gttxzisbkv.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtwytvuowu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtanvykvjw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtudltzotm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtjupffkxu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtxwhmlrye.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtjymhbdqs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtrlgptvne.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtjzwkzicj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtyvuenafs.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtogkhpbeu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gtouhjapaw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtwcwelxcp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjavvlnqi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtckfxdlaw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtqzieivtl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gtdmuhzocs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtxqjuwhof.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtkmumezxv.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtwbkjeofj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gtirpqgpxb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gtixhcjmbh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtsrxmyyti.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtdheshmbx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gthvwoglir.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gthojtpfsn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtdhnqwgoq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gtovxljvco.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtdyhfxulx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtrbpurvzz.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gteoehdywx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmmmwhnti.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxuvhvgie.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtjvblihxr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttapquthm.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtokgcemsm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptyeehal.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gtlqzuljkc.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtnnprtftv.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtglvowszc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtyeakpnov.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtvgqotxxy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtujwjyoty.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtckjogiie.html

Ruby: File.delete("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdgibibhz.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gtkyjdpcfg.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtrxuorpes.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtmujyreme.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtktxonxwi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtporwgosp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtmnsbazkn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtjkefcdvo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gtitmckkad.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtlmbegufo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gtmmzvcwfe.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtzotmpnla.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtmiixfpaa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gtmqqrgrxc.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtdloykhal.html

TS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gthgvmkoao.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtllzcmjry.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtrbiskail.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtsqwzsixn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtiwruzwuq.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtfolmbxhw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtubnzcnsm.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtfwdglfdh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtapgaqfhf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtiuajquaz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtgrmmaxsk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gtfvsrbixj.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtxtorsbdh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtmuuykxpp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtyoleugse.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtswwbvupl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtkswyvpik.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtcwmigoxe.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtnjbalpjq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gtxqjeyysl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtkdgcwwtg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtwudngpyu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtaixltdhg.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaiqpjku.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtxmgaqcmv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtqpteulsi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtvnvaejnm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtrkcmvees.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtlivtivcw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gthayrhedy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtyrqjmvjp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gtbjqttgkk.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjtazahx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtmndaymeo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtdumosivh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gtuuqxrsvs.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gtrkniwjjl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtifqknxte.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gtluoptvyq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gtfkopcrwt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtbpqcbmfr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtazwwzywt.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gteoswapif.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrabewyvf.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gtkzsucukm.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtunewceym.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtgkzzwogw.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtnpxxmjiy.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gtkpgwjude.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtwbsfpfwq.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gtiwhpxlws.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gtwfvgzrwm.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtyzitsper.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gtjaxqbndm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtbufdmoaf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtsbgesgtu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtzpzuofmb.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gteupldgfq.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtezgbqbvz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gtmhqqhhiw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtzdbboniq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwizpdct.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtbleppabs.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gtxgphbyrc.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtlkxuqtkw.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtcmxiodes.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gtckqzvwlo.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gtwkpcvaox.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtldlytvvi.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtgvioffxa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzinpmvqf.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtgbtjfzkz.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtfhswxqmd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtdvvubdle.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtnzxdxigs.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtirnmrkeh.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtwhejziwe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtyjkdsibc.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtpvfzmonz.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtuetolldg.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtkdfhrjrp.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gthqbwgfhr.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtdfcpemcb.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtwxkgytdd.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtnkjgbrqw.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtwanvixgf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtgqyyvmvx.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtystybbfn.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gtsknavdxm.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gtyohndtho.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtejukhmck.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gteokmgkwe.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvpsdumem.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gthzhwdkmx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtpxoqkmob.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gtplhherbd.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtzmfxeyvm.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtkyldyizb.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gtxrgcjhas.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtjjoriacv.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtyyuhbrpr.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtrwmexgbj.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtirtzjjsj.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gthljuihqq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtsvoeheqh.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtsoqsricl.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gtrbcvvszz.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtadabiuav.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtouyzmtbx.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gthlypvipe.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrqespqy.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtavgyihox.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtsotuvpit.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gttbnammxb.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtqgmiuqvq.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gtmvzuopqc.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gtzrrlzhci.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtffkrnbgn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsbcqtqb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtjazuyzid.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gtdunpmuwy.html


<!-- 参考信息 -->