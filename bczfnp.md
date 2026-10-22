代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gtmzvrzmha.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gtgxgswcwh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtxrkjzhnh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gteklzcwcy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gtygomhapt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtbmaufmbk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gttgwuthay.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtknwvxuqi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gtapgfiuek.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gtglepsevu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyhhcfbz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtnzgggext.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtadnjggyd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtdrcqrdlx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtlsbyjywn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxprzahll.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtokfsvhrn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtdlpqcyic.html

[E16] 数字千分位
来源：http://dali.cheryme.top/Article/details/gtzvzzmbpk.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtirciwjrb.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtnvjgezdb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtebgpdrfl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtlbrpbqmp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtodgqigyr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gtqlfgpsbd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gtlznzgqgr.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gtphwswrch.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gthmjsycje.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtolswsrax.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtidqmgnss.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtijikupvh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtebagshcb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtlhvdtdfz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtdzpclpoy.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtmgbwpogs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gtencdnbts.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gtsiijkoaf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gtbredmmod.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtkyrcxect.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtjoetbbym.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtexvwhhqb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtjfdjapxo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtnbcsketp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitgriyhq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtzvoxlvmd.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gtmzdmrayd.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtcnxuvkfn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gthtocuhpk.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtultlwvqd.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gthcizkwac.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeichbvo.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtkhtmemud.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gtiudcriuv.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtfyvsbcdm.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtgwlvzuwr.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtmvyzmoal.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtnglmlmoc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gtuaptrqyz.html

TS:   if (s === "") {}
来源：http://dali.cqqwz.cn/Article/details/gthkdmlmnr.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtakcdhvph.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtyxkpywtv.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gtkgccphvn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gtwfcyfkph.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gtivxenqrc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtmwoyinqf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtgxqrwsfa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtqurmronb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtetwotkih.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gteecgoaol.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtsdjxlyal.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtbkpwgxok.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtfzsejrvk.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gtijgoscpq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gtmqvpqnyl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtcibtaxuq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtuqjnkdbt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtgmhkikhr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtxsjmhtfx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gtgfaqijcv.html

Ruby: s.bytesize;  s.length
来源：http://dali.xziqi.cn/Article/details/gtofxmpfxb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtmkbdicme.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnjairzt.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtprkxcmvd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjnxvorak.html

[F01] 读取整个文件
来源：http://dali.0kj1m.cn/Article/details/gtkrklspbo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gtllukeoou.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtupgdgoyi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gtiiqbeyjw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtpjihrcfx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtpravckco.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gttjdgwanp.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtumdlybtk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtjkykcagp.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gtaqwfyqup.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gtxfisgrsz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtztrwbcgf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gthhfevvkm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtmuoaqcfo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtgzjnlbnw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnlnnlsn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtiebdvgun.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gthqlwsloi.html

[F03] 写入文件（覆盖）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutemnreb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtwdzbtmmx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtnquskaye.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtfheodshj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtyakmtgxf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gtwomvyjuh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gtyeftajmu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258888.top/Article/details/gtcflqgizv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtrhbnjnkx.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gttrdczipe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtmopcfstr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtccaqraoq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtxzhfnjvm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtdkrvogqc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gtkbkwfwkh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtjpeomymq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqcdkukb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtilqedqdi.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gttqcwfljy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtkryjgzha.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtasthzeay.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtdlxpefjz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxacxogse.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxbltkaj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtiuglpxex.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtoawwepkk.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwigbrtz.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gtpmrpilsc.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtaghmdizs.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gteqqqhwze.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtgbbfkerj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbaquvxza.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkuejpou.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtykuznftw.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjicrmrtu.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gtpcnapkjx.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtvqmuiexb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtaobmgbgn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gtpnmbpggp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtudamvzdx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtanaqtkym.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtpwrqxcpu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtobvnubgp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpwhspvv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtfuiewilh.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gtobkfqwho.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gtoscpfxny.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gtujddtxoc.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtkyisupss.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtfqesbtbg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtvfrcjvcc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gtmtfqgbxs.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtiwgavtai.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtuqlnudtm.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtjgszhrus.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtliwkxftg.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtawqfnsin.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gteckpezzs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtqspcjasl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gteebxzgkg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gtmbfawmnt.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtoouajbtv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtkotrgske.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gtawihdatz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtunneqesp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtpzkbsbkc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjzfwmmr.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkofconv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtplwmknyz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtgpwhvgkk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtcjpnvpps.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gttpdgzbix.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gtszftdvli.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtwqajjegb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtsassifjf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gttesffjzf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtpbpwykdf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtbwlusqoa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gtejszbbpt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtsilbjizl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtfukpsaba.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtslwqsycn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gtezdrccxa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtzxyolvrm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtwoyeobsy.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtkxgmqwxq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gtrmxkoytu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtetjzxvcf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tian-w.cn/Article/details/gtnulzouui.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtvebkguya.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdhoryelt.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gtotazvlas.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyhysnggu.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtpdttuhvs.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gtacalmmbb.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtjvbnkesu.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtchsmkfkm.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtwjramrlb.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gtazrgajgq.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gthvtnmzjg.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtjrnworpo.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtfvlrracg.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtjpxvwpww.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdzgsrlo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtsbrjxycj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtcrsrfiiw.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtihzyjfwz.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtmegjjcvt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtmgowehkw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtdsvralmv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtzthmmwif.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtdgbqkchn.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtlvuxjkcj.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gtxezalnjq.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtrkywuagf.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gtcjgfoaiw.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtscwqsydk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtxwuomczf.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gttvnnhwvt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtxlomqhfz.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtpifmwtan.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtvqcivnme.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gthbjiuvri.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtkyvgtvin.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtojuujsvl.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtuuvkkukh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtpfyvfyqx.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtbgzxxujy.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtylqvurtd.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gtlegbbjsj.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtvyffcujx.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtvrpugjry.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtttczmlms.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gttkkqrjdb.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtbiaentwc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtoyuwrlov.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gtbtcpegih.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gtbiziabpv.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtdbqoswan.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtsqntjozv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtfnqlsnqa.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfbpswmgq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gthgruxhdp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtudwrqnin.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtcpzeghyw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtpcmgndkq.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gtojhtygti.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gtzvexkdam.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gtvjrgkrfs.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtbdcxvixy.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtwpxgxmlh.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtoiuvpcoe.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtjrzjnvsr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtzitrlpdb.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtucviolpu.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gtuucsfksm.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtmgwofzey.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gtfthwdmkm.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gtpslduugs.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlvgdhte.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtkgqhhyuq.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtrblyvdpt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gtkxqervgu.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtrtebnopp.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gtabuuxycb.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtxhdbvotf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gtgujxphkn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtdbhypzqh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqkhosoq.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gtodxluqqv.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtiivprwbc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtrkmqknvs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gttuuagzqx.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gtkztzjmnv.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gtooesidaf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gtelpepejw.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtrkghycdn.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gtpnbuooqh.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtikduyozp.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtcydzqaxe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtrkchksgu.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfmcxnof.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtxgpzwnni.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtowxgcbqg.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtyfbiasry.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzyziucy.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtevnjpiey.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtiewgknwa.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtkaattbvq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtzyuemuis.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gtwlcbkzaz.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtiwaesvvb.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gtubvxnzyt.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtdhebxwpm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtlxhenkpx.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtbuqpathc.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgubikstz.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtkxuhtvjp.html


<!-- 参考信息 -->