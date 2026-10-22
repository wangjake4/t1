代发 wailian999

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtevbjfcqp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtkeygholj.html

[E12] 统计某字符出现次数
来源：http://dali.c1oappe.top/Article/details/gtcgszyohu.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtecdhhvhj.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gtjqzclnvu.html

JS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtchqqhknb.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtkqqsfahz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gtapfbbwaj.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gttrnoompq.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtnblojahy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gtntwowrvt.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtjrgoyyfo.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gtumvgkzuh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ydzc1.top/Article/details/gtezlbvrds.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtdbhiywgr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtdgrwqody.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gtecihgmmf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gtclhpuddc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtdblbjriy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtgpufxals.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gtxycrnawj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtnidkmfvs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gthwouvpsp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gtprajxyki.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtxcnrqjsi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gtvpsjzdwh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtjjrdaffc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gtjhgcjlxe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shuidangran.top/Article/details/gtrgaarnpd.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gtkfamtkjk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtlcdmxsyq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtedmklcmp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtuapmihqk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gthyvpsveg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtyjphpuie.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gttnfnylbs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gtoeikrqqd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gtwgplqpkb.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtplarceda.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtbnpnenst.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gtpozfnkfc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtcbknyonu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gteqgqdezc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtvnqukivo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gtqpitwlvc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtgviddnqi.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtzzzxbtdj.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gtpibyvitn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gttshkalbl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gtttsrlsnm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtyddcfqpp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gthmiapuaf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtqfddvyha.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtkpynlcdn.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtvnrcprct.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtnaupzutx.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gtkipvnbdy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtrwbxtuwa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gtzptcmwem.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gthoeprrnp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtbizsxbnj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtbqodijge.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gtpkljvsnq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqvzxokp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.mhx1999.top/Article/details/gtszyrzchh.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gtsxxpqbya.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gtftxykgai.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gttmnmobxz.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtyalcggul.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpnwcfzy.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtvhrdsssj.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdlrdlda.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gtouuutufd.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gtxvmmeojg.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtoepemync.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gtdqzzhffw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gthzvegtfh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gtqzjhqzso.html

TS:   if (s === "") {}
来源：http://dali.havefunace.top/Article/details/gthbsadmju.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtjrmctray.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gtzszrtwjc.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtxjzwmziy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gtiewlnvmv.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtcqwrkzqb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gtxypmsvlm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpjyyxmy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtzrocwkiy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtmedyapgw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtkfcryadi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gtnhbferdu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtlazhybkr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdxyvfwa.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gtcirkqakf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtgpvszgii.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtcfwfgltj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtlvfqlvvw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtaixbggfp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtlbdcqoqu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtxhgvovlo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtqhvqequi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtrftqnrrs.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdntdbcyp.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gtlyktcltx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjiochvxm.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gtnufgityx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtnktzohay.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtdnfqxgyp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gtuyajpuoy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtwrguyfmn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtpumtjzog.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtvmmzxcch.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtbfxspjxt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtvjcuyibl.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gttobwbnfk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtsyntjzdc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtqarnbbuc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxtwztmg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalbuwvcj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmfccsip.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtiuvyhqxq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvehmpjf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gtqocgfiht.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gttsuuifbf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtcclahqoa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtaaaftmzd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtcrjxjcji.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtuzcqqwnz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtwkbjvxqc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gtgclghcjm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtkaoarslr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtmqdoomds.html

[F04] 追加写入文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjsfbinw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtdjggouel.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtjoaehdut.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtjmczwqwb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyjwxbdu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtboiwxqji.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtupuqanlx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gtsclibsbq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtafegheki.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtzkgnwztj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtfxknpoig.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtqrxrtkzd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtuvlubwiq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtxrvrwflo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtyusgkmpc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtddkpxojs.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtpjkzldbz.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtqkxzxxbt.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhjvgplz.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtrtbsuecr.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtqjhzvlzy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtysshhujq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtvjvtpxyj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtyoxpgcvj.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtooraurpb.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtlxfdbgef.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtdavbwyhg.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtidtsnpcv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtscrpktsa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtfydcqfov.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtzhuxscqz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtkhcjwqtl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtgtrkudcf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtrdvooefr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtpiyhhjvq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gtauugjrby.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gtufyxsgan.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gtvwqtemya.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtqluykfup.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtxoxuxamy.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gthxktukfy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtszuxcokk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttavztxiq.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gtexvzpvrv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtkuwdnyai.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gtyihukccw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gthhzimcdc.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtfxlhdfdz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtueleewbs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtrlhfujrr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtmevjfcvy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gtykrxibmq.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnyathtoa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtgvwnxcrs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtbfzkrdnt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtqpwrujxe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gthkwuvuon.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwnxpddzu.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtfgcvqepm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gtnjycpske.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtzswngrdr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtzuuvtydc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtkbhvdcrq.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtlsyuqvrl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtixgdusuq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtdqmglvyd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtkwkwcovm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtrndelmco.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtnviiskuc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gtphfpubqa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwiwxaodi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtypcrljpk.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtscjekqnn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtrpxfmxrm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtnvtpdpku.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtufqhgmum.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gtotfrzufk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gthdccxtwi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gtthcwklfj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtujbcedmm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gtoclgvlqv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttsvitsef.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtckgvgmxg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlxboniqv.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gtakajalho.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gtclinykwz.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gtqgxnzlzh.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtulzsugfg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gterdeyiks.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtpluuirrc.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtxwenqsjp.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtpcdhxmsh.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gtvzybmdam.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gtltixcsnz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtmefotfyv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtybickapv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdieyenzo.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtaohibhaz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtswyhtycw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gthjfqhcxg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtiipohkey.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gturlhmwyo.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtmqznmcrm.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtndtnkgny.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoeucttj.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gthekdiljc.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gthgipsnqg.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gttlijvfsz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnwttbud.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gtrkcgjhwu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gtteqcvcix.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtwitywuez.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtirbdlogf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtdguoyfns.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtoobyckqc.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtrengtaen.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gthwaahele.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtavkobsfm.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gtzrtelgtm.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtgzcwnqea.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtmbyjlzxk.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtnaikegjy.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtggponykk.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtatrvcglj.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtzskiqaqv.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkliwejgk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtnhetnlqv.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtqqicfzyz.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtvwoxzzqn.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gteabkmupz.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtmvkokqbw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgaftdrbm.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtnmqnxwop.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtygxbbvir.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtdrezidez.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gtwhzkyjby.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtpimfaiox.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gtgimsrvpl.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gthnrccxjp.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gtutzygdrr.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtsesoyxtm.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtmkxdilhk.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtislssrll.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtsbtudxpo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgfvqndt.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gtodwhrsiw.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtmldoedwv.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtiwbkkuur.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtcojfhmjm.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtrxcbru.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtutbsneah.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtrhtprasz.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtcuzikgad.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtrrgvqglc.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gtzzwjkcex.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtudfvdbdq.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gtoghiwyjs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gtoduiufdz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcuilljp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gtdsmljqyl.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gtckdxnbnw.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtjutpqmma.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gthpbncoqg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtktofqgve.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtzevphdmu.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gtfupmpiek.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtqkwmcomq.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gtroecuttn.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gtjmoiyuyj.html


<!-- 参考信息 -->