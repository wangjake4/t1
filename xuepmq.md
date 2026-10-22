代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gt2jumgkzjd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxuhcyjo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbwryuxd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gt2sfmrresu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2jnymkhzd.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gt2qwyehwmt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gt2untbedog.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gt2zkaxvsdh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2qrzwikdf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gt2hywbmjay.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gt2xjodulmo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohhtvxir.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2psioklqx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gt2ykujpujb.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gt2qmuhaakw.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gt2bgedtxxt.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gt2omltorjc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gt2rvkgahdw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gt2tfarvrhs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gt2gkqvqaod.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gt2wetgmntm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2ypdnyhqd.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfbqedji.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gt2gkqfnhiw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gt2vpzgrgns.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gt2xywzzwsv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2ashbbmio.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2ifgcwiyp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gt2jatnvksz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2fhmtzoic.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gt2nnvtffow.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gt2nigrojfj.html

[E18] 模板占位符替换
来源：http://dali.haohaochexian.top/Article/details/gt2hzkocqck.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmuijjpi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gt2gkmjbuqr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2crujqmkj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2qvfxiknl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2onltuqom.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2uuvuuskn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gt2kiypdajc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gt2ombcejqv.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gt2xzerdqkf.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gt2ggezasuc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gt2eqfxinhq.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gt2ujeoayky.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2jsmiunmf.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2tnahvcll.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gt2xecegkbn.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gt2rdhgbwna.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gt2pslbivze.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2fljyvbgr.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gt2wijmfpwe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gt2sswlideo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gt2uwjznajh.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gt2vnybqnus.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2onimsptn.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gt2qylknicp.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gt2mpsjkuhk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gt2kvdyrbuq.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gt2okihamag.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gt2mbhhpzzr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2vanbfflw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2monycbim.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2pydjazzv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2fwikdque.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gt2wrkxpbrc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2ymqgpjgn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2yoboimgf.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrufmnsz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2beadmmfy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2yhbugaxj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2leeaiuxp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2spxezbtd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2uujeajfe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gt2wmnkunmv.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2tlfocpio.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gt2esekbasz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmckudwl.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gt2pkyenkuh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2jxbiccfr.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gt2rmosgnri.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.meibo888.top/Article/details/gt2mmvonosa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2nqmgaitv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gt2sasdqgau.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2dgyqjuvh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vyeppiyi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gt2rhwmbpyx.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhifdlxp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtnkycn.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gt2kzxowgtc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2tlifvacg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2gcwiftnr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gt2xzpwnpzg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgcsxgag.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gt2twjxauoh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gt2bgqfjuoe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gt2gnbwvbcc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gt2seaqbgfg.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbihnauv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gt2ydhavrhu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2rmlqwlqp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gt2ewyahtok.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzqhcqjx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2oadnextb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gt2qmildieo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pycfn.com/Article/details/gt2mfrqzbok.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2olytvrvk.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gt2qgebaljn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2myzqcrhr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2romiachy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2lyzuzbwr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2xttypzpw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gt2hpixmmjr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2amwoymbm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gt2mobbvjui.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gt2wrfwkbfq.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gt2ktsbsyca.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gt2lpxvtghv.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2oirxhten.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2uynlzoab.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2avolrprj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2lniwhsls.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gt2wpxujtnj.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2bggpuwzc.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2keqpkros.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gt2hdvopgfi.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2fprumjfp.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2hzpmfixj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2rbmzydfd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2vofgubmg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2qeqvraoz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2aljuyvht.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2fjfyriki.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2hiaenisx.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gt2qmrydsgm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2iukrqimy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gt2gjolkmbj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2qfsmnmxs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjeusefo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gt2hymwgcqi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gt2wtkockzc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gt2xqctbksq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2lawhiaii.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gt2guucjwyd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gt2dxpgyrzx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gt2cxmfvovr.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2oqhoxgyu.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2miqxcuyh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2wutdxgyx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gt2rbshbohd.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2ixmbsncc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2rznexlfl.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gt2dilkafoa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2qifzwpfv.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2qentsmmh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gt2modyhphq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gt2whgcjxyo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2ebfmxjfd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gt2fupkscpq.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdnfmezc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gt2ojvatfuu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gt2khkyxztn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ktmdtquu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2gwyoayra.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2ryurslwy.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ubqwaerx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.havefunace.top/Article/details/gt2labygurk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2npmxmzjv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2ckutmswc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gglxcevo.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gt2ifskxaxw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2niiebxid.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gt2tsnzfbjv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2cevcnlkp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nctikekj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2rgiwcaeh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gt2zxxkgyop.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2dphgczkt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gt2xgdcruea.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gt2iqokwzgt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gt2imxkfqtc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gt2unpjjlnz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gt2hfehhojc.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gt2ajjnycsg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gt2imhmprmh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gt2srdldzsc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.vqdsnc.cn/Article/details/gt2remyeejx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gt2orltxvbv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2vqweeuxq.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gt2zbdrgvod.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlcdbgcv.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gt2cpeqiwzs.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2zisqvvll.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gt2dtiqokde.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2pcvghxlz.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gt2rcfgyuta.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2tjjrsxnn.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gt2fsnlcoti.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gt2mllelfxh.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2rirmqwzn.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gt2irsaicpd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gt2qhdxpwzg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyawlfdt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2ucxqjrld.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gt2fdfypbjp.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2thttwvti.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gt2aiavgxmh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gt2mqwzpemq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gt2wkkanrue.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gt2dybkskql.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2vvgibgbb.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gt2zubewcri.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gt2hzfztdwo.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gt2jelcejod.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gt2rlnuaxua.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gt2zorbgpst.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2scigeykw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gt2nocmlbgc.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gt2fhnlgpti.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gt2thhgfafu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2ktgnueif.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bctcixvu.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rbybetqc.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnstbqtu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2blpaxczy.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gt2qnmrmwyn.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2tnjwcyak.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gt2dapbmwii.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gt2lkeqziyi.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2nxwtwvbh.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2kuztfmeo.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2yfkxsdwa.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2pwpfcbnb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gt2oabaxure.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2juuvsish.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gt2avzmndpm.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gt2apxfxrjf.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gt2bggiiedg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2dxdnfgnz.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2wwkziugs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2facnfoar.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2niofnicj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gt2ppjmxvby.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gt2fifrcnig.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gt2efwuewee.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gt2ixesqxby.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gt2qjoximat.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gt2jutmqfne.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2rlopfekc.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2kzchcjin.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2ddwyvejy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gt2ulfakpmf.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2pndyoqoo.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gt2obwejgee.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gt2auzeedue.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gt2phurugpk.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gt2omivxvgu.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twtnflgk.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gt2fcbyyrgb.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gt2uoevfssy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gt2uyubsuoa.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2fsodgsrz.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gt2zteecupp.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gt2snzgijmb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gt2fyuzblea.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gt2oygiwbhb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gt2jnjhbctd.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gt2dzsjzdbc.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gt2vbroqqyk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gt2abqflgtx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gt2hpnmvrxk.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdcyeray.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2gngitmbx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dotzrolr.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2ltyfnnos.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcvzswhi.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2rdrzjadg.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gt2yoxffzil.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sigtijgc.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2sdmwlgvh.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2aibxqcla.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gt2mtryhboa.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gt2bfprseff.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2lanefwgv.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2xrybqjqy.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbzatycz.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jntwzozm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2cxzczege.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gt2tldagmoe.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gt2esikdajg.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gt2awnwbywy.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2xupnguep.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2fwumfbvx.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2uoavkudy.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2eckkgrrv.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyvssoxt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2yodyifyb.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2vimgbfws.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gt2pamvaazs.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gt2ojawfclj.html


<!-- 参考信息 -->