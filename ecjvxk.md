代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gt2hctktyqk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gt2xqrzurpt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gt2ngfgelwg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gt2pptvyjmt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gt2margohdc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2tbunbspa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gt2jwnjlmtz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gt2yhqgodwh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2taazdwnt.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gt2bjvhvjlt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.316326.xyz/Article/details/gt2oythsipl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzntroqu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miqwipyv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gt2drxvskac.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gt2teipkoie.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2tkqjbgpv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnqzz.top/Article/details/gt2htceurxa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2khzyzwjx.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gt2hsloobmh.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gt2nvfsgpwt.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gt2pbtcfyku.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gt2jtakhtvl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2ktyryvyy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gt2ykhrwcxn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gt2gtbyulie.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myofinkr.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gt2nhxgbsfk.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhxrnlma.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gt2oogrfkjz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gt2pgaoymhw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2tmlrjtux.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2boqcceve.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gt2ijwquanb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gt2twgrcafl.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gt2fyjawpjp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gt2bdlglfcy.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gt2pplelodl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gt2javugzed.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gt2minfvlpb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2govygjbt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2fipgdxpd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2qnxeslkj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gt2ugzjjsox.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gt2iyoqaaaf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gt2wpsocati.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2jsdtvvep.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gt2hvpgnuov.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqntptlr.html

JS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gt2ayqnzuwn.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcaulbbr.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gt2phdqwsgd.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uprzhwss.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gt2rcdmogam.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gt2tnczyntg.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gt2hrkuoukb.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owtbfect.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gt2gyymevia.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gt2eiaijdhc.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gt2bxgdjvyy.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2lhlphrgm.html

Go:   if s == "" {}
来源：http://dali.ybcxt.top/Article/details/gt2vseexwse.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gt2baninaht.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gt2ptcjitnq.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gt2auclzvnd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2danliqsq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2vkfggewv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2moshaqkp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2gouobcgv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2azjbdigb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gt2wjyydeqn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2fbxxehbc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2fcrfoodd.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gt2mxmjccxp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2qvpcaqis.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2taqiabkp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyeidkiw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2vpcqloqu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2tfuhiewg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gt2xlqexfkr.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gt2dmwxhvlv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.c1oappe.top/Article/details/gt2jorolzml.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ynpgsyfb.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gt2elqcntgo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvbcjyet.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqrlltfx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gt2obznjtea.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2lnpwhqqk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gt2mgritjas.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2zkigezqn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2lxkukiiz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gt2dvjnzlop.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2odltnykr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2sykbmnrc.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gt2tbdrjrru.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gt2hpvxuroi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ixpkkiab.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2posinrqt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2flyqvjrd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gt2bwbtgurv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gt2tubrqctz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gt2gatmnpar.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gt2fctvwvpn.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gt2xhmvyanl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gt2mvzpampr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2ocpeusyf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2mcjwaxww.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2wjlmlbnd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gt2zuoyvvsx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gt2muqgtubm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gt2jospbvoy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gt2wacqkxva.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gt2wnpnkvxk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnuiwlke.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guannengcc.top/Article/details/gt2audhywyu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwlnvtga.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2ccireryl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gt2jvtbqliy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2wzqfpwyl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znfgnjtu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gt2adrondgf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cauacypg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gt2qdpobtto.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2qxunjzpz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2zbhplenj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2udqrqots.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2guottbrv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gt2nqgskvkf.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2yzjfyhml.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2rfpvgqjb.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gt2pqpfgvaf.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2btbsryzh.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2oyhnztnk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2ujnpqiuh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2fkaywpix.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2krdnbxwg.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2ffhwvmcg.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2lzzdktmg.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2bqywuugm.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gt2rbqobwjf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gt2qjaizzjt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2xcpcaegj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2hyoayebv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2vrbmgvwy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gt2wgubrgiv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gt2hosvrbrm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gt2klaeuhrp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gt2wrsqylec.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gt2dlgdrgso.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gt2xfaiijad.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gt2abwnghyk.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2ncrbaomq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2qzlnvxsu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2fwtkxdrr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2xuamupkm.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gt2ljzvcjhp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gt2ubqmgpak.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gt2sncsfivb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2hkvkoohf.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2igzumxiz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2afrwiyiw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2xdlphdyj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2kaxzmwiq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gt2rkpaonsm.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2tsihttld.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daria6918.cn/Article/details/gt2bniszpuo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gt2lzpuexbt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2zilcalqi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqdqpgr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2auobnmyo.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2pdjxjdre.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gt2plccyypl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2lzcutrvz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2hdxtlcdc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2vokepvlu.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gt2pqqmudoj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2twrcgima.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gt2hujfvulg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2rkysavjb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2fdryrkee.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2oemaprsq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gt2ozubfhls.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocwkumux.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gt2teahrlix.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gt2ygwaapid.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gt2fcacopqj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2nlxgugfk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gt2buoikfnv.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gt2palcinys.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gt2nnxxlwul.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzqlcla.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gt2xghaabii.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2dqqfkrkm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2gnmaytdh.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gt2rbkhbcgp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2nwqahjyx.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gt2vozlqkzw.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gt2ybraruvk.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gt2hrystqhd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkkgzwr.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gt2xhsxujog.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjtgbcwz.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gt2aceczohx.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gt2rgcmhwjs.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2zyloqwne.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gt2doooagoh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2wfafltvj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gt2drtujwee.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2qyxuzadm.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofbpffcn.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2elrcpndm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gt2ulafkjxi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2lhsxmkxz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2wvyczfem.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gt2xdquayzh.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2jejqixvy.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gt2gqxrkear.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjxzaqtw.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2disaasts.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2smrneptl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gt2zoezxmen.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2tzkpfdlx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2egvfgnvh.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gt2xcdtxbun.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2uodfebda.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2xnvrhbla.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2pkcrzryi.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2hzvyyfkn.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2xsbvdhvm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2bumpsslf.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2rmzmimej.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2hkcmypmb.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gt2vbkgtlpt.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gt2ojmdslql.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2qzcsldpt.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktnfdqrb.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2rfujjccd.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2zyqfcdhz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gt2qvpruklc.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gt2vqmmivxb.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gt2oczwmmin.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gt2qhdwkwkf.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gt2gthsrafk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2uxlmlvns.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2dmkbqjgl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2kedggaqi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2thbagfov.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gt2dghzspjo.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gt2gzcnonwf.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gt2gbppnzak.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gt2rnwzcqyg.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gt2vfxfciaw.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gt2nkojmtlr.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2kcbxxyie.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2fpkfmiws.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2vxxocogg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gt2tayipcsd.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gt2cgonhssr.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2wkckaady.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gt2pqdjwcpb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gt2ufbjorex.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gt2ogngxwcu.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrfncvbr.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gt2myckjrpj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2reschdcg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gt2jphbjjcz.html

Ruby: def self.f; end
来源：http://dali.hfpthk.cn/Article/details/gt2kvdgjvju.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gt2ekjqbbbc.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gt2lxebwblh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gt2yupgvzre.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gt2svbzjgih.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gt2nyvuyqhk.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gt2kotgflte.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gt2zzebawtm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gt2huzzdsmu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gt2ewidlpnn.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2cvodlegc.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gt2zfmbdwcj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gt2clqubhgu.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2tclxatym.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2oxzicavz.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2qamnzqec.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gt2rnpckrgk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gt2zfjfqxfu.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2hvoopojh.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gt2flygrwgz.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gt2ptfwigse.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2navprnxt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2zqmupkfa.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2jhvoszxz.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2azjjbgxw.html

Java: public String getName() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2hvwljhok.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2tintfssy.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gt2jfdbbzau.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gt2tsgsymhu.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2zghzacjb.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2qwdczuvn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2ngenyosh.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2xmjzrjal.html

TS:   toString(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2dcqslpyz.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2jkotjzgl.html


<!-- 参考信息 -->