代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gt2fvcnhgpo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gt2jtbydhkj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gt2hbdqbszy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gt2hnklmnbl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2bccmgytm.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gt2imonvhwa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gt2dyhfwgpn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fengsongda.top/Article/details/gt2tzzbzkdk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2jldhnaxu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gt2irrtomay.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngrwjcrd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.havefunace.top/Article/details/gt2kdleblmy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sulaucmo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2lsbxnxvy.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gt2tbunmmsk.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gt2zmutondv.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gt2divjookz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2rkyzelup.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gt2mxdqhwfy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gt2ysbhrifg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2rlcbbehf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbwzjwyj.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gt2vchmwwog.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gt2jhuwkgkh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gt2menrxupy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gt2umssrtld.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gt2gpvxzlsj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2rkmrvhbo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gt2xhubhdvr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gt2qsdzdqdb.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gt2dyixobcr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkcqbvom.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gt2hvuvgmki.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omthdubr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gt2iqkzqbti.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iivumzjo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2ljgycksu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2ygkrtqco.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2lggxczin.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gt2xawnpccb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gt2gycjjxtb.html

[E19] 多行文本按行拆分
来源：http://dali.0kj1m.cn/Article/details/gt2fdyvzprc.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gt2glkrsryx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2nnxttjln.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbnvbrme.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gt2ynqxamag.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltudnfxe.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gt2fbujjqkd.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gt2wbxfsnrn.html

C#:   s.Split('\n')
来源：http://dali.cdnleiting.top/Article/details/gt2arzgxsqn.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gt2xkowuqpw.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gt2fmrnkyiq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gt2gtzdjycv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gt2zpukplqi.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gt2wdkbpcds.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2kqkusuoc.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gt2ooeekgue.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gt2qtwhlsqq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmxbnann.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gt2jitbraio.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gt2yrrkryod.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2aygapyap.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2wogcueab.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxfzavf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2wilxmyac.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gt2hiyouvds.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfcsulvd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2ghmpyzzw.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gt2rlnmklko.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gt2pickyjys.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2xujygvwd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2uhiwtgey.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2duvrlxtv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2opwrubis.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gt2yiardllw.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2hdseqdjl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gt2izyxzjlz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2envzdqfu.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2inujavjf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2cgivttlo.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvutpzzd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gt2vuuhhiki.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqmbxsgy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gt2oahrlobj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2fhkmakkx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2ettmjxkb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypmdqbvu.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2trkyylmf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2gfonfmxa.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gt2zrqvbkua.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gt2yjgdrzji.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gt2xvfopfbg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2pjihponb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2yafbgxna.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gt2veapmraz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gt2ioudqajx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxylmeoq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gt2qemnkipg.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gt2oreorhqq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2emqknywr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gt2pcydsfwd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2eivuckpj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxvvigwc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gt2ckeelfsu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gisssrit.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2pxxcdnbg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2kminpvcy.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gt2hryfmqtu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2cotppqzx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rspkeqem.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2ytnekfcr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2flamfnve.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vprkeekt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gt2ipnfrwsx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gt2hqhnraox.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gt2eriyrbji.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gt2vxezisju.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gt2cdiyyzwn.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2uplktqiz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2dxmbiwov.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2vxjmvxlx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2qohpcnzq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eratqrjp.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2mjuhrjrk.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2vdkjidec.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gt2thpwyptw.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2jfebibku.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2xeiohifz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezdbuedz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2qklnzble.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2ydelihzi.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2whwguskt.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2wbjsxkpu.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2upvexgsy.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gt2dklpdlhn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2tjpqpelt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gt2whcyrijs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gt2lfukzcej.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gt2aootrhic.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gt2ahhrzhvb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.kuanghao11.cn/Article/details/gt2pntnqwkv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gt2ynexqrsk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gt2ebzlkofs.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gt2sxzuavjh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gt2yzlssqnm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shzxlz.cn/Article/details/gt2kfudmjgq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2cxrrwwwk.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2zrnxkjlh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpmkalmk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gt2zicfikws.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2vdvpwykv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gt2jafiqfqw.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gt2vrytrvtd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2veyidmfr.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2pkfmvqpd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2eavafqjc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpmimbgt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2esuispih.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gt2xrpyptel.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2goxzigdn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gt2sxumvalf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gt2zqdmzedj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2nixsqddb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2tvcgodhe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2hwtbvdjf.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygunqvsc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gt2arudzuhc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2teipvgap.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2hztzxwdc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2xvdynxed.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxhngipg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2yocfcseg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2uarkbyia.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2oxwfqjma.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2bmfvoyes.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkbultzc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gt2szqrzsyq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmbbnsjh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gt2wwfgfgec.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gt2sqpchqse.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gt2ipzxiaps.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gt2ksmuuoff.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gt2xfyscvkq.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gt2cdbbznwo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gt2uwdgpmls.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gt2dzwzbdns.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2xdvgullr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gt2iidhikkm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2uwnfkjoq.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gt2wdwdiqqp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ddrrrkjw.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gt2nwuqzbip.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gt2rsejecrh.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gt2eeetemfo.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2rqhkuymp.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gt2peqgdgwh.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2ogkkcdpw.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gt2pvfdrpcd.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gt2shemqxud.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gt2rlktjcjg.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gt2yjkbslrl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gt2vwohqpuc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2kuzbreok.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2wnwdbskr.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ashnrdxx.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xqnffkwk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gt2ltbylumj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oomunaag.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ghporcjf.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gt2pysildjw.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2hoicfutx.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2jmvxhuxe.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gt2byfnylna.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2astwrjpq.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gt2cezqpawz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxjmrnnz.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gt2ruqvrfbr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbhyeict.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gt2nmuscbuw.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2mtswebke.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2erdifykn.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2fvkhxwdb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2piswhpgw.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2nbhksbsr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2aysvousv.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2wmdhgqgy.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gt2oeiaeqdt.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gt2smmaqltq.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gt2zrvxvbhs.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2ojewcuyr.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2viteiclg.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2aiwsmjcx.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2opmcnhyq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gt2ccmscmwz.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2rpdbeczh.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2lhstfrgh.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gt2bfnhekow.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gt2vwqcpzzz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2qyozubwd.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2yenexzfr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2jtzxofeb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2cxubzoyi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gt2vzgmzrgt.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2walqyqnm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gt2cgiwenfe.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gt2swiutiuv.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gt2snqwysux.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gt2tsmmuhrw.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2ruhtpxeg.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2qvvideuf.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2kqvmuwcc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gt2leqovhsi.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gt2fuyfumfr.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2nxigvnov.html

[G08] 静态方法与属性
来源：http://dali.gaohongyu789.top/Article/details/gt2yxuypgjn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gt2arzcbavs.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lcqnczzd.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zobstxzv.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gt2skmioyrx.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gt2ftnppyly.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gt2jzzbhiip.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gt2njrrgdhd.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xtdgecdk.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gt2zriugeod.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhsryewc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gt2qeozzial.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gt2jqqacvno.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbppszjh.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2egugvxqt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gt2lfedyymv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gt2bbvukfnj.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gt2boadrjtg.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gt2ealkjzzu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iunmdpfz.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2tdcvgmxb.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gt2cqcbegkf.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2ometwgcy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gt2mswgecje.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gt2cmskccse.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2ywmwufcw.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gt2knoffqde.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdgpiadg.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gt2snolvmlm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2lexitmau.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2yhtbaghm.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2ibgyzzto.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqgeogzq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojbezzgt.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gt2zloobxrl.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gt2qpitrqgk.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gt2xgfhdauw.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gt2ilbftgpi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwxvfatp.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2qstabyut.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2xudrklym.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2qfwunevx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2ncuwtedv.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2sphjtoar.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2kgnawpom.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gt2yudrcgde.html


<!-- 参考信息 -->