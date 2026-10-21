代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbebmckp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shangyingyoupin.top/Article/details/gtnyhpykml.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtqjniwrvc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gtoiipwtif.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gthhblmnqs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtgmljehyr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cqqwz.cn/Article/details/gtpkwzcgzd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtateavbhd.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtjyhwzyqq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtnnmubzkx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtifuqpnsk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtgikwjtjs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtjcwmwxdc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtwnwnusrx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtseewqqlc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtzjiqikuh.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtnpdthobl.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gtnmznclcb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywggxglh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtrzlsstly.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gtfftjxena.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gtmhskgoqb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gtsdlkyyph.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtwhxiypze.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gtvsrrrtvf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gtmncjcxna.html

[E08] 数组按分隔符合并
来源：http://dali.gzhubu.top/Article/details/gtajxguacx.html

Py:   ",".join(items)
来源：http://dali.svipenyu.cn/Article/details/gtkugolmzq.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtacsxzixr.html

JS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtllpzgtne.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtcbhjllbh.html

Java: String.join(",", items)
来源：http://dali.yvedp.cn/Article/details/gtaczzwfga.html

Go:   strings.Join(items, ",")
来源：http://dali.iojbl.cn/Article/details/gttulrnhbj.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtxwktaenb.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtvyqppdqd.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gtbheadztw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gtqtbhdhkg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gtmmlmdkcj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtmpwmqjvl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtjindrxln.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpiakhbz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gtnpancjmw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtathqzgvx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtzdxthmyk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gturhmysvu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtkkpvwkni.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gtajiobxzh.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyesvpjiz.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtjfrodqci.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtrthhyoqr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtxqgcqles.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtssamjuqu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpopielzz.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtvdbwtnou.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gtlaxcsxtd.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthbfjdlxf.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtoachtirv.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtfspgvfjl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtxzsmvjey.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gtyrhhehnx.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtnxawwmzw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gthmpzxwze.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gtdbdqqeud.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtcmczvrhe.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gtmghhkazg.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtrcxwjsyc.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtwjxfpexc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gtdhoyyeej.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gthzmizphf.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtnuccbvrg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtolrwhnev.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtcuflinfa.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtulsdcxdf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyzsdmapi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtxvzqaruw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtzzenruwn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sweek.top/Article/details/gtgztdfpci.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtnaerxeom.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtqznczceb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtxluiowrv.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtcdzccvco.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtpslyskph.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtgjmhrpfu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gttxydlhhv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gtqbkctvpo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtpmdmgqss.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtovlduzsj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gtvwdvdvcx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtyquintxk.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gtrqyvryfj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gtiykjirdc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gtvpfajegu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gtqwufvdok.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gtjpmjxobl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gtpoohbanv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtrvvaaogn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gthfffavss.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtmqgjotfk.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtjsjvrzqs.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtqpemzgzu.html

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gtbcrkiasl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtgzmvmnre.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gttkztbupo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtecdpzdka.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gtrqcbxdin.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtvmblwzjd.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gtdvdsjlgl.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gtkmzzovws.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtaujognbu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtdkjtlaii.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtzllakljp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfokqygic.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtzwfawfrb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.bjfxy.top/Article/details/gtniorpxsr.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtjtqfnlkg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gtswtdtvok.html

[E18] 模板占位符替换
来源：http://dali.hongshengwenyu.top/Article/details/gtggkzdvrj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gtpioelmsa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gtzgslhrlt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtusmlztaa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtnvwavztt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtdbykmuhl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gtvssjgoru.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gtaesxotjk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhnfohco.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtnruwfvxe.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gttrgfygjh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtlhixwzhk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtsztcyvlf.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtnzddpfja.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gtppnqjlwc.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gtxqoflxzz.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gtlkypkpgc.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtkknijkbi.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gtojzlaxbs.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gtwyaldool.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gtsnuofdny.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtebadqftw.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gtumlotszp.html

Java: if (s.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtwalxjkxz.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gtkilwwrlx.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gtocmbexla.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gtwpbijdlz.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpumpmkk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gtuopylpsn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gteteyxyoh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpullhuh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gteohhgpqb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtolvtzizp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gtendmezvd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtlxrpagdf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtbdfxiacx.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gthlanavwr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtfhghteck.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtazrelsix.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtivmffzau.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtbhetafuv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gtqnrfqvry.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtlfxeyfnq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtzewdiaww.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtbqxbprsu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqyburact.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gtnbzomxvy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtufaapluc.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtxgknjvms.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gtotftpocv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtdohghoss.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtbwmhutur.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtbwuoljtx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtsmutatfq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gtlhfyhrfk.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtdbwcycja.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gtiryjjuzz.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gtfgyxiiph.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtwybiqkpu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gtocujaroa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtqxsxzpoq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtcddawfov.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtfiawksno.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gttptsfpri.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtmdqzzhmp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gtmoyohgjk.html

[F03] 写入文件（覆盖）
来源：http://dali.yangfankeji.com/Article/details/gtrbkonzlk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gtukkaorlu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtbhmoffzn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtclholhyx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gteffkpiuz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtkqlemwhl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtxreyruev.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtsvdmtjsa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtnipkaeiz.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gtcqhbksjo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gtxjdqjvph.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtzxvhzfzw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtcuebwyob.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtrhmniocw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gtihbvicjx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gtxpombfts.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gtioxoukol.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwwtejwv.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtzozkklhy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtnmpcsaam.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gttfbdsqhu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtsscymmyy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtvcoztvvk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjbiyklf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gttxnhmzgo.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtegbtzrty.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtidzxljju.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtjrfeyfkq.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtrwbrootj.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehjobrha.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthjfgqnhz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtcwmvkerw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtpignxing.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwjclopqw.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtgjuvcsfc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtzdgyngtc.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtflatjfxg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtvltloirz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gtwgwruecd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gttvsckltq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gthmgudxcf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gttvyhycjk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtbvjrquok.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gtbqlskqvs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtykstcdeq.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gtrigwvvjr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gthdoyclrf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gtrgxopsbo.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtoblfqujw.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gttpkhiyze.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gttaixctrv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtsuhhaysq.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtafblvbtx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtrwxldrzf.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gttmrxbixc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttcredjyh.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtrdrmmzia.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtqijizbqz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtkcruxxwk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtwgmxahwm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gttoabdatw.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtbwuavnkl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtchgzezyk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gteecsuxco.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtvfvvtqey.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtglaopqci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnrmzsluw.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtaihgccjg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtdemchlnc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzsffwalj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtwlhcdptp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtyaprxiys.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gtdkxmrtdn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtjyhqvtce.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtteoukndc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtkjtnzsac.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtdzvnlzji.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtzboipeyb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtuquczuej.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtdzozfalr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtnnhlapxg.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gtkwzbmwfe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtusmflgzn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtndlblsil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtewbfhvbr.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtyyseljwc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtkctygiwy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtowdyajah.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtltaysnft.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtpnkwjxbw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtergnatqf.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gtnqizwhxs.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrzuwqhva.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtaormahmq.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gtbcvrhhga.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvnszrbe.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gtqakyyfoo.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gtfpzufzha.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gttrvqmarx.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtvryybcaf.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtrdpoiphw.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifklciys.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gtfpumnbbu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtysgzbdio.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gthimlcuvh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtjgpugyvl.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gtovitjyyp.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjqekhjll.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtafauyhdv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtuprmtytp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtrussvvhg.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtybadakst.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtxybxxpil.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtzlbysgmo.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtubjphyqz.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtuaveyoqa.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtoojipcgv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtxdxdyqbr.html


<!-- 参考信息 -->