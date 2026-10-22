代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gt2uzhyyfsc.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2ltqpgpsn.html

Py:   s[::-1]
来源：http://dali.sxryk.cn/Article/details/gt2clgyanvp.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gt2zyttmjnj.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2ygmvxxpb.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkyxgaao.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gt2vjhrudnz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2ycckokzw.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2aopdijkj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2iwsvsdxj.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gt2zjutdaqc.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gt2tvgfcqtt.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gt2psoefbuw.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2xgghdief.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gt2zgszyltm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gt2amevlqiv.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gt2azcteezx.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gt2ifaqnxaw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gt2mrbczcwa.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2tnfgkmzt.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gt2inejxljd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gt2wfnzsolp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2nsodnjyc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2cljhfgdl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2huxpvtum.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gt2pynxxinv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gt2xtxwppgw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2lrefsvkq.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gt2dzvhrqax.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odtbhxrd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2nnejghiq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gt2dfbqlqnt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gt2hpevdkhw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gt2bninmvqa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gt2jfoucdml.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gt2tdzuqeib.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2dbuuootg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gt2cyckrysm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iimgzwnk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cdnleiting.top/Article/details/gt2ahodylss.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gt2qasikmfn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gt2mweyypdc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gt2ijrcwixk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shuidangran.top/Article/details/gt2manjfreh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dijhopko.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gt2jviodbzg.html

[E16] 数字千分位
来源：http://dali.guannengcc.top/Article/details/gt2zavryivm.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gt2ritbeess.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gt2eservuut.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2nqgpnwzh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2tulmfmkh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gt2zzphqeja.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gt2ybedhiyn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2ewdqjisz.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gt2nsdwmhef.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gt2gtlwxiiv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gt2dksiaqoz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gt2vqlwmaxh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2xqetdsst.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgbcvjmt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gt2ioelgplw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2yhmoidkl.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gt2ddxjicvb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gt2oagvkybk.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gt2diecupco.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uerfzytn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdkviklg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2hxrkypmy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2nfjogpvz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2kuosvdrd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2wsrsbvhu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrkwtarl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2tfychxmz.html

[E19] 多行文本按行拆分
来源：http://dali.yangfankeji.com/Article/details/gt2fvxdvyjr.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gt2frddzziq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2waozcrfz.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yahiltab.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khqilbbv.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2upsaqixq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhpwvajz.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gt2ljqwddea.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gt2obujhckj.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gt2hvxsftif.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gt2vktcecnc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gt2tjefuqnn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gt2gtrlzsgc.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gt2vaivuadm.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2onsmrvos.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gt2whkiyvjh.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gt2vyruuarl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ripmwzqz.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gt2dkilieaw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gt2taqhzqzv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2zzakxyyk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2sxrxnxkm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2otukdytj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2synluasd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gt2eufuariu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2fxmqbupc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2vksezvqj.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gt2nsomynyf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ptfjrocb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2bggpyemy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2mevqcvas.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2dhsyzrar.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gt2rrkifkeg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkkcnvm.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2xretdeig.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gt2ztqrkeov.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2rghoxguq.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcmnqtwo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2buqkrnjn.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gt2usfvgwld.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gt2alycwnnf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msorzqay.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwnyogt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2wzgazgrm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wykuodlw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gt2fwbnxevw.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2vlpokfew.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2treejzqn.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etokxxye.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gt2jecgdned.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gt2tlrrnoxy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2iaflcjxc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2qutwsnwl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2expeeqox.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gt2srfmhzoa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gt2diawgbdy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gt2kibhpsui.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gt2jchbupve.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzkzpkqj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gt2pockgabl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2nnpujvln.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2ftlxwcqu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gt2otsbutwl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gt2bgjssaxc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gt2uobayiiq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2zjjpilus.html

[F04] 追加写入文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2wobulxms.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2ysvgdkxn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gt2ntpwkcud.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtuuqfna.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxazmssa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwbxzjau.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gt2ybrceoxu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gt2cfajdtee.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gt2urtodcnf.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gt2mghtetkn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hammf.cn/Article/details/gt2bwsymwmv.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2fysuuxrp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2pdykezqa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2tegrdpns.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2oyezhwvb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gt2bchsolqr.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2tnthdgvy.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2knrzhnfa.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gt2wereoypy.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ojgsgznl.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2ynyiynui.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2arvzftgr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2iyjuvuwo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2dczmwiov.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2hmpjorvb.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2bkzmdnlr.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2plvqbysd.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gt2ckxgztgc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2isbrjtyz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gt2ukeoijqo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2qqtnxtjn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2txgyuzrk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gt2hqdpjawy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gt2enjbyugl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gt2svkjteaa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gt2vslsvorc.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gt2pdbmivqx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gt2tiqqrasy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gt2gsbjrvux.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2niqjwmdv.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxnrruep.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2jlgijulq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzgfhmnp.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2dyjgsmzq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gt2pmmyyytw.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gt2fcnvmbvs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2pnduumrt.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2zbhdevrv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2qlvfkqmr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gt2ydsdprml.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2uhiqugpu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gt2dusyposj.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kurlzfmb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gt2vvjjfgpx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gt2gyetilie.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2roaflykh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2jryzrfcj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2gqoyteak.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2qghnjogp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gt2rxpblvby.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2dynxmpgi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2qavdgjpc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2qphuylwf.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gt2ygtpadah.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2ifzkterw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyaqtonp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2hpxtyoyi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ingknjcr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oixybipz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gt2skernnfq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2huijodzr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gt2xzizyeik.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gt2lbhkbfjv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gt2dmpnitjf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gt2bnmezcjv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gt2doitocnb.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gt2kaajsxzy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gt2auzejccw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gt2spbmmfyi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gt2bzehcfbb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gt2azjycjqx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2psgtbfwl.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gt2umxldecu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2timrbiwg.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyoufjjj.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gt2zfzoatpp.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gt2cmmwcpwm.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2ddnqmioj.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elxgsveo.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2csphobvt.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gt2bqlwrcyl.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtkkyguf.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2gdoszgjj.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gt2emhgqdqt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gt2ikdoyxec.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2brbyadbb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2ebcfkyyo.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gt2ulyyhviy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ynumaiex.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gt2zrkjqxdk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2yaeqmamm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtebywql.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gt2lssosxyo.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gt2ivrfotcy.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2mwfcexkm.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2lwiezzvm.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gt2gqkmzlud.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gt2socmumjc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gt2scrxkbjg.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gt2sdbmznwk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2hwxjmtjj.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gt2inlegcom.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2brwjhvtx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2apabtnse.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2nxjbepch.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dolgsfhx.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gt2lsasomki.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2hiwdekvs.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gt2cdvtnqfb.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2yvqjtqqz.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gt2nqxozajc.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gt2kkqcypcz.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2xrscmryr.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2syvetppy.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2lhjnvflt.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrukmmjs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gt2jgxxbnon.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzmjjgdq.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gt2qbasslga.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gt2ogtrscui.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2rzfcrjov.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2yhclmwek.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2hhdpxnie.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2lnfscarw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2sccmgbtg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gt2geaymlzo.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gt2nwezsmtk.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gt2ywnumeig.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gt2dvxgptvg.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gt2rrncukat.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gt2easyjwom.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2npulaacj.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsukvfat.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gt2lvgzwxng.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gt2fdniasnu.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gt2qsmmlghm.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gt2sberwuef.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gt2mzuyxizm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpcvfyps.html

PHP:  public static function f() {}
来源：http://dali.redwolf501.top/Article/details/gt2sumnkiza.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gt2joxrnwvu.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gt2pocjmtdk.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gt2jqrluink.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2kntjapwc.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gt2eyoeobfw.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gt2widvnopo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bevbttxb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gt2khhzciot.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gt2xqxywzbi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gt2cbaytdjl.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gt2ifzzoidn.html


<!-- 参考信息 -->