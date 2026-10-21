代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gtdohhrjse.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtjhhdamwl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yonumen.top/Article/details/gtjispagqo.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtfdfmdftq.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtborlibtb.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtqqecytvv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnucxgrbg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtsiwampzn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtchvnhxvh.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gtvdzkehmb.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtfdwxuojd.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtpuqbgvmy.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtxfogyaov.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtbxhweueq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtcxdndqvj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtlcnbrdvo.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtlihbegwj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtuqzxmrhh.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtlxdnnwbq.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtwofsymle.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gtihtmltpe.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtwbrzcjbm.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtbduvovtn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtsupyvcyt.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtuyjiaton.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gthtizfppn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gtzodufdlb.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gtwmiotqdl.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gtreqszvbf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtgshakdaj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnypfkmga.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtqgtnvhth.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtkmmdjzhh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjvdilwz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gtifqoydqx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtrqevxnne.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gtrelcyqqn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtzkhfhyym.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtiuwilluy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gthdvdller.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shuidangran.top/Article/details/gtbhzrphpd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtjvyygcep.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtfdqpwpbv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gtvmxmrfoq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gtlomvnrst.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtllwpkjyx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gtqjldvoix.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gthtgldxsf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxmthtjx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangdashe.top/Article/details/gtxpmhkwrv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gtpfndikgs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aizwys.cn/Article/details/gttyfifurx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gtljlnfsdr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gtefdyoefg.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gttbcpkhsz.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtijxxpbju.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gtedmgqlwa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtavjemavm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtayqnvswt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gtrxddldye.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtzdjmfzey.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gtknjxnbjf.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gtdagjbjeo.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gtknnujcov.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtargjnfcb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gtvlzefgkw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtrbgtvwry.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtysweqmtk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gtygpfyevd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtglwisnlu.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtowyvuxsw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtkjmfbjal.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtegwzplfu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtulmptfvz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gtvekuobsp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtwdmbygya.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtfuggmohd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtivjgwdcv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtoraetvrq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtgmecyenc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtenphnwpi.html

[E19] 多行文本按行拆分
来源：http://dali.tian-w.cn/Article/details/gtdxldggpd.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gtntxfghds.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gtbpbxtwnf.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtwxxynxqp.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtjlseetsh.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gtudckubiw.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gtmvemtjbi.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gtyapmfzsi.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gtctdxwyfg.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtprnbahig.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtcamlgrkw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gtmielvnwp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtrahkcjms.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtbptrfxzc.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvmhsnck.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtvnjbhzhh.html

Ruby: if s.empty?
来源：http://dali.daria6918.cn/Article/details/gtrgadkihm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gtnmcxmbzy.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gtbyuwuxly.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gttlxtumza.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtxiqseruv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtfafqvecp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtjlnyceni.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtkdoduand.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gthzgpwhoj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtqhtyjoeb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gthzsltyhm.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gtzfxkdmno.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtcmpggkmp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtzcjzxeak.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtoltbtrol.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlygneazp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gtuvctmvno.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gtoprfmisi.html

Ruby: s.bytesize;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtoqfglqzz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtekkuosox.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtgvhlbwcu.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtshrfhosp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcgxywzzw.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtdcbtgvgz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtcxbcjijz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gtdtabtzaq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gtqabgougd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtoctkgazu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtgttdayse.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gtgxhbitkf.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtbqgbzekg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtwlgvpxbh.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtfqguiufo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gthyrhyzbv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gtpxtjalik.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtyujrlght.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtqaliysbs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtrnkzxcnl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gtafxohxai.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtqvvfpbdh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtzmmxfivc.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgoxccxki.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gtokwzfkrf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtssdautds.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtkfdqiqdm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gttvbmqvur.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtvcpetxdn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gtmwzbaxtl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gtpwrbitnd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtwhyvsvyh.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtzjgmjiqb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtolbwpwzy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtkbjussai.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtqlebsyeh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtaazfmljc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gtngznpsze.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtufqctufi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtyhucuxwx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtivuzehlp.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtvkpeghgz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gtydqmgzwu.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtikevswqb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtzygaqrrk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtwthlykrs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtglmhqrwm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gtarkdsids.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjwhgxmxn.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtikttyhpa.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtbqkspxhx.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtqnnmsocn.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtdjyqmrua.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlyvgfdqc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtyowmmjae.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtbwobkohb.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdvzqfgnd.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gteugluren.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtavnyteoe.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtnlerfnzy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtfacjxirq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzvmjbdr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtrmjmymqp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtxquuxsds.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtrbiwjypc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gtjhqsqnvr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtsstiftoe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gthnmzyjca.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtqgiryqlk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.iojbl.cn/Article/details/gtuwlneekb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtyosokxep.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtjhivdksd.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtewqkhweu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtbbzgfjar.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtbrckhwfp.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gttiatcbpy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gtxkfyfraq.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gttzksxjoq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtnloqwzza.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtofxypbml.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtrtmmldnb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtvohorozj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtedqrgbnx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtsmtebfvp.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtldbzkxoy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gtkvtcznhc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtuoydjond.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtbgpwfmak.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtjfxjykkj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtepdgmstt.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtjhijseza.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtvsdcihzj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gthxdjupeo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqlhthpqq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtxkcdcuii.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gtqsoqhisg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtnyzjvloj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtcglcbtso.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtidgkuufo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtfbmioxau.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gthqxidtzx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtkptxvsos.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtmxjxonyh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtcyuwcfan.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtfthslfky.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtmohgcorp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gtdovucsqc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gtkvemztzn.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtplhwbnxf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtzcqxuhkq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtcaopehyx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtolbexywv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gtrbnorsyo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgosikqnp.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gttzpkqsxc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcaogywvm.html

[G01] 定义类
来源：http://dali.hysaishi.cn/Article/details/gtqhixwkwm.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtcoxpdvat.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtojpzchjr.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtmnsbtgin.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtsdnvixcz.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtgodedcbg.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtjakauvea.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtrvrgabfi.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtykbnxeqm.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtlaynnyxv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gtyoxonxqw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gthgminepz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtviqvrjhl.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gtkyyjkezt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlluntfuh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtevfblsrx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtwdholsbc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gthhkzmcar.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gtzxxekmgn.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtkoiftbvc.html

PHP:  public string $name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghjultmj.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gtrmmpardy.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtlnryxvjs.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtsitolfzd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gtistkyaet.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtoffoiijx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gtvoehnqov.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gtopkciivs.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gthkcikemt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtybsnvcgp.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtivghzfne.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtlycwscka.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtxwsymerm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtdruqqxau.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtazvjkfhl.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtlraorflc.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtrcvurghs.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gtcaqchksp.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtqhjvbidg.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtrolvhvgo.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gttutptbsk.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtxvmnqdex.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtqdaliima.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtjibzxzcf.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtskkwmmca.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtzdjyktsu.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gtqtszbyxy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtpxgmbtao.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtpkfldhlr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtyjhfwltj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtyjylrrit.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtpkwzbtxc.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gtnbbyhpaa.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtgzatarqz.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtckslljkc.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gtvvlnxjxw.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gtsutlfzig.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtlqjzvvuz.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtpwpfvpdn.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtesysksfz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmricjdn.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gtddugysfz.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gtysweurnj.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtjuaxoebj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtecndkctu.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtyoztxlrd.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gtjeamflhy.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtidsiwtvc.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtyrdwjwrp.html


<!-- 参考信息 -->