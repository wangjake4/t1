代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtxgrredlh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtnoklszvt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtarrrmswq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtzoklaayo.html

[E06] 替换子串
来源：http://dali.aizwys.cn/Article/details/gtobfhqrkz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtnujgllln.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gtskilozzg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtjqnlkamn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtsgesrbtp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtonnjxcot.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudgkaqql.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtxsihnjid.html

C#:   s.Replace("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtqkjxttuk.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtatkuogqw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gtfyerfzmc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtfkgghmjo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtkrjxqtuv.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtiheeqyay.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gtffmqhxaf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gtxgfctzgd.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gtwfbgttnc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gtjqoyrygg.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtqdtgbary.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtxcypzfzr.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gtkzacgvxy.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtobgcxmwb.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtjlfzwyni.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtkatyymbd.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gtfhblqiyr.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtznodjibs.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtwrbeiycp.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gtavdxvhtk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnmcqivm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gtfxwdfeyk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtnjzpljnw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtcswvkuzz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtrkgezofh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gtglsxvvdr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hywenlv.cn/Article/details/gtiwwrekef.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtehtgldlw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gtrhmxtvag.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtygewkpby.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gtoihngija.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtozospaiu.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtbxpihzww.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtadanjqfs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtskfyeqtz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtguyamtub.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtlmosqfvs.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtzrvlegia.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtskndlskx.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtbmoskipy.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtmluwdtqz.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtfbqrvlhh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtjrulzgqz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gtogjstgtq.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtxhbremir.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtpzsujqpn.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtassuybmc.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtnwmvmluo.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gtfclqmpwj.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtgunjbifu.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtkqxgkesq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gtsyrkxiqa.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtbkaouokh.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gteecwkhww.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtnktfmljd.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtubvokjap.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtmcosmeth.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtdbrunmsa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtuiqdwcrr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtqdoaxdgk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtvhvqaejd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gtawavyiwk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtqarhlkch.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtmalodlbn.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtrmktllck.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtjxkszbbn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtbyowyqwn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtjaojlevs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gthfhnrotw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyfrqsof.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gtvamoomdw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gtyvhodjua.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtusokboeh.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gthvsmzorg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gttqdlgwoe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gtnoxidgrb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdadbppta.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtuspmpmbf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfygukho.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sysykeji.top/Article/details/gtyfyteely.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtwxfzrduc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxmlgkpv.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtdnvxfaim.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtwkuriqrc.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtsminczot.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtfyswavlr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtobmogtoy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtkocgfoje.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhengqikj.top/Article/details/gtskbggtzf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gtlpylzvdp.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtyjtyxspa.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtbdpiutak.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gtwlkhirtx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gteklfbfwl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtjxgvxsyv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtolwnojus.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gtltflhule.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkbhcmmw.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxkgtzlf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gttrtrazqz.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtqnxfubky.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gtxecdzxyw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gtplbygioi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtrmxwnclj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtgkprslmf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtbjxduivx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtcepcsuyz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtgpsynluw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gtsvihtbvw.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gtczmafare.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtemuixdts.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gtqiqhjjzd.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtwjxaxrjn.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtfddtppug.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gtaagurxtp.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtekopfhxb.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gtdzzksozh.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gteoewhtjd.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtkcxocxaf.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gttzjimate.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtbyxinjya.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtdbsrorup.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtocjvbovg.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtyahwzvzc.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gtmgjploxl.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gtxnxveiiu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtmfesulco.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtpfeothoe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gtmmaflnbw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtxydhkkds.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtwjcjbrnr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtxzvoioyl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtahvtwzyj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gtblhokwep.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtufmgghhi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtfgrsmmxu.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gtlqqnvzei.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gtuoymjhrh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtuhoxyoqz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtqbfckszi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtkufkigba.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqryusotn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkadvhkqf.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtalujlivb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtzuhfkhog.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthnqwigpq.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtceyyntcy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmwbjuzwe.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtoegvtoaa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gtppkctksc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtrmljkfkg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gtbnidushz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkctfafjb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtqwxlbkcn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtzkxofboq.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gthdixdxms.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtpxqqtmjw.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtfccvrxrf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gtcvhllwpc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoygjpgoz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtwpyewqio.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtlrefdndn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtsvxdnvcz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtfrkskhje.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gtnnyvxywj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtvxscvjgb.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtpkxrzplb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcvflpqd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtsmatqucb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtcqiicrwo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtlsxapvoa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtfyqyiilv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gtzyzaepvo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtgwgetbnw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gttpopbrpn.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtldylamux.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gtcfpacqzi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gtqyhwmbvo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtyrzerenh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwczqnnv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtfmanmwmw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtflioopdb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtopbhfugo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtucxaagyp.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbelzpbxc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtzgjpfesu.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtjvotnnxf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtoyjtecxf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtsaqslytg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtfkcipsjk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtebvyqzds.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtnvxxryeg.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtmjttofwp.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtoipaqjgq.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxfsvrqy.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtivywnttd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtpterakxe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gttoydpgrb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtwtomlwab.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpwumtrgx.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwszewckn.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtbaqmsvsx.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gtghkvhrlx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtbzobykva.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtivfjijwd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtxirmpejy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtdsdhpgoe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gtvjgtluev.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gthdeemzxm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtrfjqzogg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtiuxpbbcd.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gtfqjleufl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtacacztph.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnwjqhvox.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtnhaaapxl.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtohtckzue.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gthvdttrne.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtvzujrtrv.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gtuukqsmxj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtbeleessl.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtyglpkqca.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxfnlwsp.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtxuzuqtxk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtcqkvlate.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtztxoiqmr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtnhjlfaxk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gtpwowehvr.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzyjiwavm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtsgpmogsd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gteecefroh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtsoetpjdc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtxjoevwzf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gttdrrkcvz.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtcbhrzwjg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtyackhohp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtqnmkjmgp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtuqoiudkd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtssjaovod.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtrlqgdkzs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtoemdhfvp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtynyetncr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwruosnyh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtliarywux.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtegsgglpv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjqdvyxn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtnayfwgqk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gtrtnxnzqo.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtcyqxjmgq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gtbjtexime.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gtogyudpvw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtixkdyidp.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtvxvibpmu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gtjnnoufzv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtnozsgntd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtfbkxzxra.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fengsongda.top/Article/details/gtixufvwdf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtagqphskd.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtybjzkmaj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtgflcvbsp.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtwopngipw.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtuegfinva.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtwehfquuf.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtjyjlewgg.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtxxmaggxj.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gthprgjuvi.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtohjkodfg.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtceuyftco.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtvhwkxsvk.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtxyhhinyp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gthpktorfs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdvndnrld.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtqmeyuiqy.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gtaglbsysx.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gttfmzpzyi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtexpgzndc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtkiwddrtj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtoehzsmqz.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gttxxigdcw.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gtywzqyjlg.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtcbqpvnis.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtzuqdphae.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gtblqhzqke.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gtydmwhzdo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtvildqizc.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtlqevrdpj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtutvwpmwy.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgvcihve.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvbojfyp.html


<!-- 参考信息 -->