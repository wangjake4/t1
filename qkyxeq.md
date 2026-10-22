代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hfpthk.cn/Article/details/gtrcdrztej.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtuvyxgyqq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuetiantiany.cn/Article/details/gtfabzcyhe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gtiuvffwyd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gthiruhouk.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhengqikj.top/Article/details/gtpylpqufo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gtihqekklr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gtlswwunvs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtogbpenyy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtemcavjcp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gtmemfbfwi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xylfe.cn/Article/details/gtbafcizfu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gtlyklnwbi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtaolactep.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtileirkmz.html

Py:   f"{1234567:,}"
来源：http://dali.smart0.xyz/Article/details/gtchulfrkb.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gtnuglxojn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtyclghasf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtziwbuaum.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtxxchcjjb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtmdhnjtri.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gtwjknoixk.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gtcmcabxui.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gthadylsej.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtxxjjrobw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gtfqidukhc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtvejsttmw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gthutdtyni.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gtzvdliosd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gttzavgnea.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtlijecfyq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gtlfftcdsd.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gtqxjrvdjd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwxcbdnu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gtzczsfnot.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtfrlsliju.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtvebpetvw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtbwtfjuyk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtnudtqbgr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gtlflhvzvw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gttccblgjg.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gtsxexryaj.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gtstgckjnb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gtjlpvasuj.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtvxzqvkae.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gttswlvsim.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gtntlaaxqv.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtltqpddvu.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gtafqcnaqv.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtpptbrojo.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtaceqqfec.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gtzjrulkpt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbfuiflg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtpcdmtvgy.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcodxaijj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqrblseaz.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gtfiudcmkl.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gtardzctxp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gtapktqoks.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gtoxwjgvzn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtkvszdadw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtytzdlxsf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtabdwfuxd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtxtlzrf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtxxzdshul.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtraazbizy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtfyyxedsj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtqdmmkydn.html

[E22] 字节长度与字符长度
来源：http://dali.cashguo.top/Article/details/gtrskfmshk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprobuaza.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtdmmymcxk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtleyftmts.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtrafsyhkf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtjwdmimsl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtguxpyoic.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gtiyzexfih.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gteftutawp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtidhwrbbk.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtmrsxbusy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtchdlshiq.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliuttakl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gtpofosnis.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gtmjpepcyh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtpihuzzxp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtuhbowhrx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtkfdccfhl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtrrxpldji.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtsthnktlq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtzztjmvae.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gtkfyirwrf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gtjruivlhn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gtojobwpcb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtchkeuets.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtxdrszyjo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtnalzqsyz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtdzmsjkeh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gtqtxbfrtr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gtbctazzsc.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gtboarhotk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gtoaqtkcxw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtgdaumdkb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtdapcidki.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtkgejmjyk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtgyppuwyh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzaxovjp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflmggukv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtcvpehncs.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gttyyqofal.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gtrjebmnsd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gtosijfgfu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtukfoahvx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtjdutohbk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtlpubqwif.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtgtxhxups.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gtiwjqbryl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtpeqdbtrq.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtwxopfzzh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gtpdesscbj.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtpinntbkp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtamcujetl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtyycqgwrv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtxdthzuki.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtzcaedrkg.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gtsbzvnviq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtaysxqjew.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtfocyfdxq.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtxpxidovt.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gtmegucytj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtpqhkndwd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtcbsbloql.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtnnbnnzrz.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtfakzxxwp.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gtdcwoqgud.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtunmqodre.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtviinkcdc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gtoiftziit.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqckyhmu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtgsajvwbz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtnrnysyfl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtfwnqqeju.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtyeqjefmc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtggcajenu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gtprligfaq.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtaabufwxc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gtvqentakl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtnuqvystp.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtpndewxrw.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtstxbxekg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtfcpcxovq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtmefsmhvn.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gtgehwaksl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtnoihakmm.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gttrvaupem.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthsubqjhq.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtmtdfixsa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gteofonoju.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtumwfvjif.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtlbgdjzlf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtnphtrvly.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtdmmuthxs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtrvauosnz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtdnqafskz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqojgosoc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtfzulkymo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtcnxlorkx.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtntgmwnpy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtguittrck.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtghjpavps.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtyryzlewl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxhbhwrps.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtkqmdhcrs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotpuhyks.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gtqvbiumbh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtkvptjgza.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtyxeqdeyi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gthdiccuuk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssoojvfm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrpcyolyx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gthewamxue.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtehhpimlc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gtumalkidq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtniykqjwp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtvcatrega.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gthuvgbbnk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gtpxgeqfqz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwkbvipm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtutnzmvqg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gtymewlrwb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxwrkakoo.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gthuufrnif.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtchdinlnr.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtxuplfrym.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gtcanxdgzu.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtivrzunyw.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtcgomtesw.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtuwgfexff.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gtvuqhjouw.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtmvtrcwot.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gttypflcvo.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtfyzciomt.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtojrfwgbk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gtbhngdawu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtrcszfald.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtuewakrhd.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gttpnmgxzu.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtiwcomqpn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gtywlfhzmo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gtqaormogm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtuqkvhdkj.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtzykuplly.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gtsmxsiaqa.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtyjfmuyem.html

JS:   this.name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtutonltqc.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtmwrlqszv.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtgcqxclmx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gtduifqaaa.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gteontcofw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gticrdghpb.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtgepwlghl.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtzpqeylyo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtgnuqszrt.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtjfxmwdhy.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtaougxuga.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtszjrkcwg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtpxgpgypp.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtyzdgdeqq.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gtvkwjmssb.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gtugapfxoc.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gtrfqcimmt.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtmactbwyv.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtoewwknaj.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqympesum.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtzfctozfm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gtisvkqeil.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gtbwkawuom.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gtowidxfac.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqxvqbws.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gtvhiqqhyn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtnzuiqeev.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtcywpsuot.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtizqbqfii.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtswnzqdfx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtxcaepodh.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtgcnprroa.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gtxtupozay.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gteyrxvprx.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtbbxgtdrl.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtedotgvjy.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtzmbkoiry.html

TS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtdsafdvtn.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtgmqikunw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtxvhzpqlm.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtqyvkwdft.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtfteaqfsc.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gthrzmmnea.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtcefokgya.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gtxpxzfdmh.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtuovclkug.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtvzarhuba.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtwvfqenan.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtgjvqqjml.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gtdgirqlxh.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtvbcnrrbc.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtxjgrbyis.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtdxydjvph.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gttpfmvmyp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtqfmkcank.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtnobfztxk.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtpgpomrgv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpdcjlda.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gthxndeaee.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtquhupdit.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gthfkazmfo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gtelpjuitw.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtmuhckmsq.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtfqhbcilq.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtnnkmibid.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gtzvywbiio.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gtydjntuls.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtmhrqipto.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtnmbtwlhm.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gteiuinpjb.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gtpbhahvoa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtpuzllkjm.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtfzopdcre.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtncywaysp.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtchcrzjrk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtlejkpexj.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtgokgidxu.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gtkaaqctzg.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gtqdtzynfl.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtqvykwars.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtvlnuiesl.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtmatshftw.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gttwdnvupc.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtnbihwcpq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtktycwwkm.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtzvyesneb.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtefbsakuq.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtikwwspfj.html


<!-- 参考信息 -->