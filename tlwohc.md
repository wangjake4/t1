代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gtklchkhqf.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtovojheqx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gtjbcuozkq.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gteskfsvva.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gtjquigtmj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtvruubnir.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtxncanoou.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixhyyoby.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtbmmqmxwu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gtmnmgcxxz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gtdvxighlo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gteuqggfls.html

[E14] URL 编码与 Base64
来源：http://dali.shangyingyoupin.top/Article/details/gtbgfmsels.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtrvemdtlb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gtbumsofwn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gtljaymjhb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gttediiusu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gtalaxidll.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gtnatczzgc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.smart0.xyz/Article/details/gtcicqcxaq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gthvecxamj.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtzncovqqr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gtgbaijbqf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gtpyktjsgj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gtleccztxe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtkhouefrg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gtidxlpwgc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtpnokbffb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gtrctctmch.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gtbbfmcyox.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtpubakhtg.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gtdyqnmuji.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gtabcuxakt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtiuwnshte.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtpwxayvhl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtnnjufwaz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gtmsuqlwvr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gtjwuahmus.html

C#:   1234567.ToString("N0")
来源：http://dali.xuetiantiany.cn/Article/details/gtsxtlpjve.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtlrfsrszf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gtbgnfaacj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgievmlm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtphimbdrp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtepxdqnbm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gthlcgrjyk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbnormbj.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtvfziflwh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gtrhggarqu.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtoqkbfjps.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbozmtemd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtrdasmgea.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtarngduia.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtrzocehup.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtdgggjley.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtfhitgoft.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuxming.cn/Article/details/gtspplfovy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtzebbqseh.html

[E19] 多行文本按行拆分
来源：http://dali.0kj1m.cn/Article/details/gtazueiiyr.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtzjokqord.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtoycbgaxr.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuusrdgzz.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtcbqnfcle.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtyrxhaosf.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtnlipqtvh.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gtoekzwwvn.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtbsrkavrx.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwhuwxex.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtreqhsuku.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtwreclfin.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtcvzkjtyo.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtpcfcqpkf.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtcziaetls.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gtecxuxxii.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqwovgyg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gtnxsyfunn.html

[E21] 超长截断加省略号
来源：http://dali.yueranfly.top/Article/details/gtzfkebrge.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gtqsuqngdh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtjzgfgolv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtesaqjijv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtvvadhuit.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtrvvxuzbc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gtwvssxozc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtmtnelftk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtcygpmtjv.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gtjuhqtwbc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtjjgdirud.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtzlyozsua.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtoqbhrzvm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtjenqrioo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtcwxcqrvd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtyzbqavmm.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gtqmkhgyss.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfohxigvz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwqmmipky.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtsfqmtsmt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gteapeelch.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gtlpmvedut.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtexjvqfws.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtvuebxhpx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtbooyqblw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtptgehsdo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtpeuefwun.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtcrftivua.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gthkacffui.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtdybwuptd.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gtuubksnkf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtobqbpqxe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtkxjavfyp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtvcblekbu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtecbvbhks.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtnudgaqem.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gtiokrcopb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gtdlvxwfsk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zycfv.cn/Article/details/gtuqjgkcuo.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtdbhrdife.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtnukiuvew.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtzhsqthwu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtlarxzjoc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtfnwkqwlt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtnrxwkuch.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gthctbvphj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtyrfqiyda.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtdgzczxtz.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gtmfhawpyr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gtglcgnaff.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtcncdyqyy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gttfgmmcnk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexhpwkhn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtlukvkzlh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtjdjspigu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtelxkpjon.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gtvdvlllbq.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtrfpjkgtd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtinkzxzkr.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtxvtaknhl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteclwazcv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtdnklogcu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtmhofnbxb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gtmdlmwfra.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnsjaxmks.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtgzaziqzu.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtvzhmcaud.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtxcbwlokj.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtbnkfyimq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtyeaghsvk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gteqqkjtpl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtxfjtzosx.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtkvzzmpzp.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtyxqhpyou.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtivawpogc.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtbqnmogon.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtunbtksfc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtnhpbytqc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtxlvczror.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtffdbnxnz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtypdcckfo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gtkgljooiu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gtmpcelqfc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrapvdug.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtqfglqbio.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gtvwvyfzva.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gtzscqaego.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gthxwhmnnc.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtwoegqyji.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktwsxdwv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gtilinlbia.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtuvccdxve.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtogmmnzra.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytzwjvbz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgtupaclu.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtnxjcfuad.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtxzeyivdl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtjwosgfjc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtxqpgcqql.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gttrbywnjf.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtofryybpa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gtgshggtms.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtoxgvgxjd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtklwgidzz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtdjrpfbfp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcpduhus.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtggdjoxhp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gtzgodziql.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnjufkehl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtlcnonnim.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtvppkvivq.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gtufrmyyoi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwknmuqf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbcbigch.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtdnejsztp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyjchown.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtzunstnto.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gtdbugccav.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtkppoldhh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gtemohxrth.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtcvezvurh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtskjwarik.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtxaaybuck.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtwepgbvod.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtfemgyzcu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtndeaqdki.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtdegzwsph.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtibqosjsh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtvybqctoy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtuynfzesr.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gtesjijqby.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzjawvxyt.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtvgoevyjl.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gtwxnnpodt.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtrufjxsae.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtyiepulxs.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtowjvsjmv.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtzhhzkqkz.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtgqekkqfy.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gtfstcfgiv.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtchzsmhyu.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtpiyzjpba.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gttsefxqfl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gtphwhmtxn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtlwnwlbue.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtzunttgbq.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtxchwaant.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtrayfyllc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtgngduxqr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfdfbwua.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtiwgqmxbw.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidkwizlf.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gthhqoxopx.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtezyxzwwq.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gtskrbbfkw.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gtjxuqhthn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtggvhyjmn.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gthpwpaoei.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtrvizxefp.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghplcxdd.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtnbftbkvx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtyblufiup.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtplaizise.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtedhtwcuj.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtexvvaikb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedugfbnm.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtjaykspgm.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtgpxwuhit.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtouhmynsz.html

Py:   class Admin(User): pass
来源：http://dali.zhoulong.xyz/Article/details/gtnhouvpdw.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtlaqgqccz.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtfmqsetuc.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtgjvhjiub.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgnucyvbu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtagqofykl.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gtqkjndtfz.html

C#:   class Admin : User {}
来源：http://dali.nwbrower.top/Article/details/gtxrqbkexr.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtldnbcbtr.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtiilksmzo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtvnbajohf.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtyxfplvhm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtepdgspjc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtwzlloubb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gtmyjarnuq.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepwtuzwx.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gtedjseinh.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtsopabbtf.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gttfyltlvq.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtwtsxgkbp.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtjhpuhkwp.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtutcviepy.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtdehdzoip.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtklppzcyk.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtsofcsxhg.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gtmqzuavel.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtpvphnnsd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gtgzagvkbt.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtfuunmmji.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gttkyzrexm.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwplpxqat.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboxbcakb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtzinipglj.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtefpprfxb.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtsrcwekqc.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gthgokbyuh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gtmmcjkfvd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gtenvuetjr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtleiagbxc.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gtgejoenid.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgiqnjmvq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtwlnjyjnf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gtejtmmotu.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtxbotgdrp.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gtenvyxyud.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gtedzhcygv.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakqcsirz.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtnljrhxsk.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtcfmjfmrn.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtrczebolk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtrwclhnuo.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtiruyvolf.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjboaglos.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnsyfrmg.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtvxcnyomp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtlzzdigfh.html


<!-- 参考信息 -->