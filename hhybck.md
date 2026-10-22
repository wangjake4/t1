代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2lvxrckkd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gt2fkokmgnw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.meibo888.top/Article/details/gt2tcpddkgw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258.top/Article/details/gt2nvqedvxj.html

[E14] URL 编码与 Base64
来源：http://dali.cashguo.top/Article/details/gt2urybzyvc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2ryzhbauw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gt2diftsemt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gt2kzmzfrjx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gt2aapbxaem.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2eejyoytu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gt2czibysey.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gt2nxravghk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2dwqprfds.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gt2buxbadjs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gt2aivcbvng.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gt2xorqsukb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gt2hyxaodmc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gt2wkeeaayz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gt2tdcyckfm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gt2tbiqrawy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2uhguxgua.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gt2rqwsuuya.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gt2bcrsvxhd.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gt2ezsevajk.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gt2kuvziobt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2eisdjvjx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gt2iawzfwzi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gt2kvtjtzwi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gt2mipxshvv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghsjihep.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gt2utckpvzp.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gt2grghcffv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gt2wzbmrtsx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ptwbfbtu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2bzjnuuhd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gt2axbxdxrj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gt2ypghnexi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2gnkdzbfi.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gt2esojjjqr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gt2winqanpg.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oibczdgb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gt2puvbpjcq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gt2ferbdgvb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2fhvuscep.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2ykeduljf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2wmgsmpbq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2repqwfxx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzhunylp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gt2vewuildh.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gt2pujvklwo.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gt2xjbfzvmz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2dhgnrbcb.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2pqosruqp.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unritdcc.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2ffaagooc.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gt2kznbsgyp.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gt2qebsdvnt.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gt2txdjjcxv.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gt2kwgiygzd.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gt2svsdejnl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gt2gzrakcyx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tybvqbln.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gt2wkaqwkek.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2apbgzsdf.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gt2xqyggfzz.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gt2gfecjscq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gt2xqxvlmkm.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gt2yxyhniaq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsrlurnp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwmlbwvh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2kbnehnnn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2ntndppdg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2knefvmwd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gt2ewlaxmcs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qacobobz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2dmgdzupm.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gt2eflnaprs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gt2amxmmlao.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2bxbxiifa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2yescxfuq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2gjirjezm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2wgktbpcu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gt2mdpsvwaa.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2txjsljgt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2zmquiquw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2glizcqqi.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gt2hqipadzg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgehlhbu.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gt2nhrkwijr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gt2tkkodtof.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2zhyuvtrj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gt2udaxhcia.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2ixmvbdiz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aykfmzpq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gt2flxiwuuq.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2lvhrvfew.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2pxakvgus.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrivaoj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gt2xthkhipw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gt2sxjtazhp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuvapuff.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gt2hulcpgps.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2siguvogt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gt2miyhxmxe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gt2yvxrpqdv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gt2qndcpmgt.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gt2oartxvwh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gt2hzzzsxmf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2zefcevjq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2eiuvwyzq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2lothbowr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqthchct.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbhmcfhv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gt2hxjaxamw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gt2sxozfwat.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gt2slxjyygd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2nfkbpkha.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gt2krmwahcb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2qbpnaiex.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2zbbevizt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gt2jznolidy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rraejjdz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gt2viprfrnj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gt2zymbxkkd.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2eajxslpj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhvobiag.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2jrfefsmk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2xfszymlr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2vcxjyryk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2alamljsl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrlwsxfk.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2zdepzbhr.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2uzxnhfqi.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2twbxqgce.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2mukvxvjy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrdzzbi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2wavltdsk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2cyfvscnz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2fscnaals.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2hajvzbwr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2nbqzqqzo.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2tfnbhyra.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gt2yiopogqp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gt2nyfmpeeh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gt2iebwlnuj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2ivxzldgq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gt2yqgecwfj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gt2pfopktex.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gt2omnkhmmg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gt2krhqezvv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gt2ioppnvcz.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfwxzkya.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pyrillzj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hnzkuiyt.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2shwputzm.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gt2ddqvzdxa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2spjwkbdz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gt2vgkgxazt.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2cqmkrjva.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gt2ukxmmjoo.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gt2wedycnpb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2tykzlifd.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2ladhgefj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gt2uavqhkxr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gt2ykgptmeq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2jkpqmnzp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gt2zngustcr.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2sdhsvmhg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gt2qevenuke.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gt2cenrnenx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2eusjwkxi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2efyaogwq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ivagbwhu.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2zzsmuypy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gt2vyzjdqpg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ucjioges.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgkesvnc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2kizrhayy.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gt2saopcscc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2knkbtsum.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2qtawvtkw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2twvjdjek.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxiecyya.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2tnlstrph.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gt2zablgzzs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2wrumuweu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gt2zplirzkg.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gt2adayaaqa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gt2kqoklitv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gt2fcothmog.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gt2ryulmsfl.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gt2iuddbkcj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gt2jgtuyigg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gt2emhojjdx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2hwkiyfkd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gt2arjvhfds.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxtlahiz.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gt2mqakhehu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xtrvvzhv.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gt2anmltyhu.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gt2pgljxmor.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gt2sefiyqha.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2tnfgvuit.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vsxivyob.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gt2ytveoyli.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gt2zhyspbsa.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gt2iuityzyi.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2acerigyd.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gt2bygcbkxa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gt2hsouvkcc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jerahrap.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2npnoftud.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gt2titwvyya.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2hyqzunpr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aiemdnmm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gt2gsfxgied.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ecflxsqr.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gt2jtaboxgh.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2dkgfugwx.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcelihgv.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2rrntiqru.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2vpazxitb.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gt2htgfptrx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gt2kqmoveoj.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2gjvxsrpg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gt2owbwccwm.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gt2cxtklebt.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2uycvbpyq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2skrezedb.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2hqbrrzta.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxuwnrgw.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2uecjgfle.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2gdqoreph.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2bfksnttv.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2aojxdjys.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gt2mlnbmabw.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gt2wpudiayf.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2jafmquva.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2kfdtktno.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2axtcdswz.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2kdjcfvhc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gt2tpyfmtmr.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gt2dgxmabrt.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gt2zurcszzu.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqrxxvqx.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gt2yiuethgi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2egleeabe.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpxwjoax.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2uwhyciac.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2zwmersoh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2tltjelsh.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajepdyov.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gt2howhtnez.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gt2kqewoows.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gt2fdpvbbus.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gt2vxcptxju.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2ljzxbhrc.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2wqayidqm.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2ptsshrpn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gt2bywrmcwt.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gt2hhwnyzya.html

C#:   base.Greet();
来源：http://dali.0kj1m.cn/Article/details/gt2yzlfrzmq.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsfbwxxw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjjrhvqu.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gt2ftujqxob.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2vmcgxsvw.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gt2nburswqx.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ldusvven.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gt2nrxfaihm.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gt2pkycilak.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gt2xbsoicya.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gt2sojcihwc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2srewzadx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gt2mnwdefiw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blbsrtpm.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gt2vfbpaggd.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gt2kbjemkpk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgqoptbl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gt2hzopfgcf.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gt2enolzarm.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gt2oyjkkrbc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gt2bsagatdi.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2syqlxqog.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gt2umqtajjs.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2fkwwpkte.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gt2optkfgud.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2emhbsbra.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2rypnzrhu.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gt2lelpihnb.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2itfrrguv.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2iirhdloc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2vhierskq.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2ztouxgqx.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gt2eryoypro.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2lnfzpysh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2nlvdwica.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gt2fhppxuae.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gt2qumoxarb.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gt2iwboffyw.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2isdunngw.html


<!-- 参考信息 -->