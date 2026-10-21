代发 wailian999

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtgvhefyjc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gteachpfvo.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gthmudmfwy.html

Py:   s.count("a")
来源：http://dali.meibo888.top/Article/details/gtglnsmtdp.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtkmecawhy.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtkknalsvx.html

TS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtaqnodbel.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtsldafdoi.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gtwxbdnkoe.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtkkpmxitq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tianlin.xyz/Article/details/gtezzxrhjl.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gtxjxswkuh.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtwsdiqagr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gtewoghssc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjsypvibz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtgxzeuzki.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmccxngp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gtwwfdgehl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gthisrasiw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gtkjfrkuiz.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gtudcsmffs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gtgkzprrfc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sufxvd.cn/Article/details/gtblnncqgx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gtiutpqxqm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gtwyglrsns.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtoylvxgxq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtuwpfpvbo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.havefunace.top/Article/details/gthdyartrq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtmwbxzjpd.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangshuangyany.cn/Article/details/gtrurrggam.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlbubzqht.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtnhjbremm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtwxwztsdq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtccvpfhcm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gtabdaskim.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtzhyjhdzj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtmagudcry.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gtwbhjqqwc.html

[E16] 数字千分位
来源：http://dali.hywenlv.cn/Article/details/gttmdefvvq.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtzosjxqlh.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gtdfgxuqzn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtvjfdylrk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtfgfesubz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexrygbli.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gtqvejiqes.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkbuqjmq.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtzngwllhh.html

[E17] 首字母大写
来源：http://dali.chenzaomai.com/Article/details/gtbztfcywr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gtpjffxnva.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gtjxdkvzns.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtrfjeegow.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtgmohivot.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gtbcqcjgav.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtfkiiwwxe.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpqigvmg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gtdgnkbmxr.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gtjvjysujf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtvkrokprl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtwedgburd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtyipoxosx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtencdxhxs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtstjhhhtg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtefkbzkva.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtqucwhgpy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gtjdvxagin.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtvdnvftyq.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gtwqsuwrzl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gtxkaohael.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtegahgtxy.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtdxhfzwkj.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gtoykvfsoa.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtpmdxlmlp.html

Ruby: s.lines
来源：http://dali.jinqigufen.top/Article/details/gtihlsebdl.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gtpeiribld.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjlsofzt.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gtzknmittk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gtbnwjcnjq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtwugjvddz.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gtbzlepzbw.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtljdalosc.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtiuiwmxvl.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtqdeaxwss.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtepbpghjk.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gtfjezjwjf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gtaazbteuz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gthdxkslqt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtecwmzqsn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtkwzivdrw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gthhpdpqxi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gtjggksrwu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtzlbjrnke.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtfadyfngk.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gtcoffhtmq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtvhhjtrkk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtjjrkdiwd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtkpgwdnen.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtykjpmemu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gtngwzdlhz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtqgockwpa.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gttgdgvtxr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtxgxragxa.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcratgcth.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpudtsugp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsuqchjo.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gtpqmatcij.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtmzvgoqxv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtykebyfid.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gtovkflkeg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sweek.top/Article/details/gtrmkajqrb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtyeqriiqa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtcnumfjtt.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcogmkrbo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtskarejxu.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtsrxnqyam.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwbomlfz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtralymorv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gteoirnfmz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtqcljpfpt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtagiylnlq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtzuhicbdk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cheryme.top/Article/details/gtgneqahhr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtanyjcjsc.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gtllljigrg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gtqsypsnho.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gttkrpwbwg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtoxodinty.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gthckcvlhh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtjrspqxlm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfycogchf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gtqdxriofl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtwxgmexjf.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnufqjjc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtdgrzcpbn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtaqvfhrld.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahcauhxz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gttumoxgcr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuxming.cn/Article/details/gttzqmvlmk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtbqrqzdcb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gthyllufru.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtifmhlhyl.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gtfebypvdx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gtinuuqfqd.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtukbupide.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtacjevowv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtxielvwzg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtadjgyhju.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtxdzjyjom.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtpkvgbead.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtdlptlwvp.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gtciwfuncq.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtixkwmmwx.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtcmaxumkr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmjysdjbk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtbprxjgox.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtqkeqgacf.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtxzdedqdl.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtjnnfkkpd.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtloiljknd.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtpaydcyao.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtodfufplp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtvseadnso.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtevlfazfb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtzpkawwiv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtxqtjuctz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtvcpiaeuh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gtwzoxgynx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtniptrbfp.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtjjrfsabb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtkyvdfgno.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtxxzinnsc.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtxxzjepec.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtlmexzorg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtmibjwmhg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gtwhtcsxiw.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gtsayktref.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtybmxyckg.html

[F09] 获取文件大小
来源：http://dali.zhongyouzk.top/Article/details/gtepplztfv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtiroyvhax.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtbfybywwm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gthjvluzjy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtehhiiuhe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gthdywqlkk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdudqxcfe.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtroewypke.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtaoibecno.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtrmfnbmgx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtjwbwzrlo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtdhnedfly.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgaseswvp.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtcwymugtb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gtfadubbfh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtyzeruiit.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gthemrftld.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxteqjtwp.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtbtuzqazn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtghpvdzkc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtfgnunexw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtxqkawaix.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gttyyskhzb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtcbwufdmt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gtdvfptvkf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtptbuixmo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gtvtyjpciw.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtkolbhvgb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtrjdjawlv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtfoufagyu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnqzz.top/Article/details/gtijgyphzq.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gteftdxbus.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtpkoscjce.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gtxtoeaaru.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvcwmyct.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtuuipywwa.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuozgctis.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzqdloyy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzwobnsuc.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtipxlpaex.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtfqmtcrqo.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gtqwewlpxh.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjydoadlu.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gteedjrpee.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtiqydiuzc.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtficjdcjy.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtsueltdtg.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtnmoauzje.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gtpqsosnuv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtpjgnvofw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gtrwwfucmd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtydswwbkn.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmrvrzlzf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtevbhgtjh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtlloqmqky.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmrupgyd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtnvbvjpsr.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtbxdudjzh.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtqmhahpyk.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtkxnpkjah.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtpigvrzpb.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtpoehtkug.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtzuxzzcvk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gtotmxgazj.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtswyrxvpi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtyrfnxbnn.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtwcywjsoq.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtparnzovs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtalwkmfqv.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfcifnji.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtpsfquqeb.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtufyofsiy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtdtqbylrh.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtsibcdrkr.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gtsmuzfdcx.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwamqwsaz.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtuefueitj.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtglhdcbot.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtvyavifib.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpdspxjvb.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcltehehq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gtsyewealh.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gtughgvcfv.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gtedeoikyd.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gtbocskdqj.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gtdqcorzui.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtdufodffh.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtivirdprz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcixlgkag.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgrnoqnzv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtlyoxamyo.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtefqhmivl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtpxwoixss.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gtturrcugv.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gtcnqlvqcs.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gttlhbkgos.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtdbuyhqjl.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtwqavjxdk.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtohaukbdg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gtyitejrba.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtpyyfkbfx.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtshedvzlk.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gtwrpkpdtf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtzbsreweb.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gtltirnfyp.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtqoqtnpkw.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtgtcpddag.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtpmbjyojv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gtidwsgbem.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gtlnyqscfe.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtahsrcteg.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtzgixbton.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtwhwumtsd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtxcaikdml.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtvomoacvc.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gtkzhcnglz.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gtyjvqxrix.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtxfnrwvjw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtbxylomwm.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gtyhjrayln.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtqzcazokd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gteigoegts.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtifhdjerh.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtzkfanzkd.html


<!-- 参考信息 -->