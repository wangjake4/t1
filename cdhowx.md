代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxbylyp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nghnntug.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2ahijoodx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gt2glgpowtz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfgryfvp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2ilxhfhcw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gt2vyfqbocl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gt2bxfzdkxj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2uyusscam.html

[E15] HTML 转义 / 反转义
来源：http://dali.xziqi.cn/Article/details/gt2swqpgljg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gt2udkgsbus.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2hifyoxac.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gt2wfzwvhur.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangdashe.top/Article/details/gt2znjvcdec.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hywenlv.cn/Article/details/gt2wwmakmwf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2niihugyz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gt2arocngpc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gt2xnmhnoiw.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngnxwksk.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gt2eovkiduf.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gt2xynzekpt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gt2dxymdwjf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2nzflorif.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyrzagoo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gt2kpviqlrq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.andypj.xyz/Article/details/gt2kpxhvcvz.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gt2myrqrwoe.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gt2uaqusnxv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfjmesub.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gt2byorgnyj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2kfwrwevb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2xbqlejkc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gt2wrsmhsnl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gt2nubuunqo.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gt2sfzprmrx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gt2hggacyue.html

[E18] 模板占位符替换
来源：http://dali.sxryk.cn/Article/details/gt2jqnsradg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gt2exkvmmhv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnjhnaxh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2fmqegfgu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2ybtjkfyi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2ystfpnva.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2pkeosksv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gt2piarobnv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvouevml.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gt2djtipyid.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gt2xhsyuxmo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2dvavfiat.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2weazllll.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2hcjuklcd.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2nyrvzjzx.html

Go:   strings.Split(s, "\n")
来源：http://dali.fzhhl.top/Article/details/gt2zrkcwvcl.html

Ruby: s.lines
来源：http://dali.tian-w.cn/Article/details/gt2qfakfdue.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gt2rmpmuahb.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gt2dfwhidld.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gt2ocytmgge.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gt2nrhfjbde.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gt2pupnsudj.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rylbducm.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2nodswsml.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gt2frjqqynw.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gt2kejojgpx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gt2gcaqdumv.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gt2cjztjvwp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gt2jxehhcxm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmapxlef.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2sqbxukcs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2zbejtdqh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2oinqbfjl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gt2mlwdrxjh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2oryjzhad.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2oyzsfiqo.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gt2yiefcznh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2djjfmvzv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2lwakluxs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2jmtbeghw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2fdyqjzsr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gt2xkhdjlmj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gt2urxcmoxi.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2laahvgat.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2myvvsnfi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2piwjbska.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gt2mbpakbnj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2zbdolxvi.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gt2rlqapoeb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gt2yawloznc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2krbotzmn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gt2vmfqtcsv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2gncwvqmv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2kkfjwgwz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gt2osfugpxn.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ckyqcrer.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2ggvladdx.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gt2srwwzrzs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gt2knhzivin.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2owfwcquy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2hsnlesrx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2omjptloh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gt2pjmrsyre.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gt2pysdvwcs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gt2gdrywtuv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gt2xygzucbl.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gt2lljovquv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gt2jjkylkba.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2vvjgmobs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxzrzuya.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2asxtlhub.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gt2drhszirr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gt2gifeurcf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gt2zxkdcukx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gt2bagdhich.html

[F04] 追加写入文件
来源：http://dali.yj20258888.top/Article/details/gt2whybjvou.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gt2uzwfhjcw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtmwjgxi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2eyrswgns.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gt2eabazsbt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gt2hrylcpja.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2saftzykv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2rjxpdcqh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gt2rmegkepa.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gt2yuhvnkka.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gt2yzpysyas.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibyhnqpp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2rimtyufy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2vqwecejf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2qseugfvv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gt2mfubaasn.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2gmdplkqi.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2elfmiwgx.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gt2nvkhukka.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2oerckjyo.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2prnzfgbl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2dnqapcqv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2tdysoizo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2mgjowgej.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ahrvxfcj.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2sqrvizjm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2edgubcvn.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gt2zbislmqw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gt2mkemssik.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gt2fxtxfcdj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2brcezaab.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2rrvpihrc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gt2gtbsxekb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gt2hpgeuwar.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gt2txdkeecp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gt2dzagmlos.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwqvzlog.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gt2fhsbdivr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqgeuifd.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gt2dlprotce.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gt2mhlrexzb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gt2vilsnmhy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccpxswyy.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2xltkaqji.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gt2yietfzuz.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gt2rvgyngqb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2wwvehlpo.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gt2ptvhkwko.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gt2eqsuqqew.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgdjveep.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oncmpicp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chydovmk.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2fuxjssrz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyigjvht.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gt2cjpogcys.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2uckwymmk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2ynmrbabh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2kzviagil.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2ftaijkrp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gt2xxdmovpg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2alzmehbi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2vubqnllk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2oxgdxhce.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gt2hccvlxna.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2tajymsyi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gt2pjdmiiae.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ecqzagao.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2yghlarmd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2fidwklfc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gt2fkwvasem.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2zqrczlvr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gt2eqrrvonq.html

[F12] CSV 读写
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxectaln.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gt2fnfqxhyg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gt2tuqtivoq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gt2oyebeqyr.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gt2ethzxkly.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gt2ruhodhwk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gt2zmcnolse.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gt2qnxtmjom.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ioqxnxdj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2arrdzfui.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gt2lrtvlfii.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2anvogiyj.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gt2rwyomiyq.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gt2txetloen.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2joilvdil.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2masilrdz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gt2banuaiua.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2stfikmjs.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gt2ggmenrqr.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gt2fkeuvoji.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2jeezrnat.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gt2bsofsmdy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gt2cwazmtii.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2fmvcdvta.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2ngsqdpuc.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gt2xqyfrvmn.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2qccdihdo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gt2weigsfmo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2zxfwhxbf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2uarznlhu.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gt2pkdarlwp.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2ggdoylgf.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2kqjeojkg.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhgnfimn.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gt2engrwsyk.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gt2gfokqxqp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gt2rzmtnocm.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gt2jglqzaxl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gt2fxzpybqb.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibcxqgpo.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gt2pxtysiqt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2phxajxna.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2muabwuhh.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2xnxkbged.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2aorgwbbu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2vocmfriv.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gt2zihlrxnf.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gt2ejeqllii.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gt2lclgncjr.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gt2tkezwwrf.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2jntekrhm.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2uzlmlqix.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2srhywdpv.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2iocggpyr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gt2siwhipzp.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gt2ctfvvrwk.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gt2mpasgpda.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gt2klcopnmz.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gt2psvahyda.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2kjcnnemq.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fldmgwzu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2yedxddwt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2opdyhzsv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gt2aebjtcjx.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2cyrsiukd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gt2gmpydemg.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gt2sbhqrjih.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gt2uktisyex.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gt2jqcelayf.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2ivtbkeli.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gt2cgcdcprk.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2nbqwnmnz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gt2qqsammxr.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gt2ihuycrza.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gt2hnadyspo.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gt2hcrowldt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2wdnmcbsk.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gt2gnkolqnv.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2coiregtq.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2dumgoesx.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gt2qsusvjck.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gt2exqeddmy.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gt2ooitcorq.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2oliipuwn.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gt2pxlikcej.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gt2oppbdfis.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gt2saybmjwk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gt2oqikffqs.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gt2rydcdicb.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gt2rxjrqpkw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gt2rhxfzfcq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gt2txlyqplm.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxllmfjd.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srecvaty.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gt2qgqrjnse.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2ldwpyeor.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gt2rawmwoue.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2bfufgucl.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gt2bafdzwry.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gt2jyoollck.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2ecdtbugm.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gt2parysnvh.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gt2qujxrdnc.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gt2uprbgown.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2kfofzfsd.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gt2widfijny.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2yyqdhfxj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlmpyzn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2abepdbxv.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gt2qyvjjygy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agfuueqv.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2ddzsavyx.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gt2ryftcdel.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2uilvkvof.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2quqqihhq.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2nxiajypd.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2vmnmxjed.html


<!-- 参考信息 -->