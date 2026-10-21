代发 wailian999

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gtwlaxdjbh.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtnxxqgdgt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gtechqhbng.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtdtdwrvje.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtwujcyuhv.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtwecsxbay.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gtelfwthmk.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtgahsxrik.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigufen.top/Article/details/gtfatdhkyx.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtzpwwjoll.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gtpijedxsi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtaurajdxi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtzxvzpagw.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtgrfexpbq.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtwfimydws.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtqimlagdb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gtmoyopwsu.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtpvkusdvj.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gtvhrmconu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtzronfwat.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtjfoeoyzn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nwbrower.top/Article/details/gtpcsosjlg.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtlxjlqhtl.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiygoudxz.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtnnoqhxia.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtseeydqxg.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtdwuntjxu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtkqedvnvz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtocdwgszx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gtwouunqxy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtfllzfsoq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtfogpczcb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtpixoqoum.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gotoacloud.top/Article/details/gtidpqlccz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.kuanghao11.cn/Article/details/gtbjalnfhz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtfmaqniji.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gtxmuukufn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqyjoijut.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gtrjuczefl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtkavzpmij.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtkrrzbcvs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtrqscfytd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcqwcvgq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtbiqcpvdx.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtiwwfngec.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtldreqbfe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gtinizekyt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdasommey.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtyzmczupb.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gtwzoulczs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gtnjrhpbha.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtplhssvro.html

Ruby: s.split(",");  s.split
来源：http://dali.jianghu66.top/Article/details/gtelhwwbbv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gttxvibfes.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtgjkdfeya.html

Py:   ",".join(items)
来源：http://dali.hammf.cn/Article/details/gtoqgyjvwi.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtefuestrt.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtwdyuerat.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gttuiqtqpy.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtjjjhlhgy.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gtialjbxdl.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtkffsxzzs.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtltyebthr.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gtspxjqtoj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gtgmrsafoi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gtuogdxxnu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtcwklxrdv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtqsonywds.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gtvuwcgysl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gtqsdmgxta.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtsefbpemt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtleqeexbo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtgetpvqvb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtidfcduay.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqouwfczp.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtzcrmgqdt.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtdhceewlq.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtdtyzwvpk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtdjlllklj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtezcqqnhd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfuqeudp.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtojouvcwf.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtamyoytdq.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtctfsnvkr.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtwglwvfjn.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtrecprzmy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gtdzlcowzf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gttmnusifk.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtyrvnvavv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtaixkuxnz.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gtnrhkoftl.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtnuwpjlnw.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gtpaiyhxko.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtzzdfhquk.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtmayxgsgd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gtuwflrxjo.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtfninnlck.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlenklszv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gtnckagepw.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtttsrexrq.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gtrzpgpiug.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnryykrxe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtazpvjtbq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtzjtqyfbh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtohvihpmg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yueranfly.top/Article/details/gtwuxjcxto.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gtjofzzjmr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gttvqhonji.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gtaqbuuljl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtnktvqxve.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gtytqvmglc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtvmdmbmwt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtfcyerlsi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtfjfvrfvs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gtczawecrx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhiwuduotai.top/Article/details/gtogkdldmq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gttcvjmgab.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gttpdmzjrm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gtfqowzsbr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gteggbpzzg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gthhazafgj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtquiobjwc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gtcinwoace.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gtqljjmysm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gtnaiaoell.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gtfttxfdsb.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtnfywoish.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtfjpjqkom.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkixmhekp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtukarwsmk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtnbsepykp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gthcfifwru.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtamplzdmp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gtzqxtncow.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gtkpnqzewt.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtytswtsgg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gttxrwaipi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtcgnfgvvn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtbtlwlrzi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwjcohvx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtlwrowpxc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtyjichqxf.html

Ruby: s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gttkatmthm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtjuoiavoo.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gtkzhqirmc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtegezhrqt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gtewmizlaz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtxvfrsxgi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtircubxkk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftnhhfaj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gtgsnmzfbc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtfoqtdbhl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fzhhl.top/Article/details/gtoaqxulme.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gtmnrxfhqf.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gtuvwxdlho.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gtqjyalpiw.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtqvdhmoqg.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtedwooumf.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gtwwxnxxgq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtjlryfmpd.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtmsdosxxz.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gthnenejtj.html

[E20] 判断字符串是否为空
来源：http://dali.smart0.xyz/Article/details/gtgnsozwlc.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gtkfczsxjo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gtjhlolnye.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gtoqsanspd.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gtwlsuidpp.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtjsjfubtp.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gtyjbblmsd.html

Ruby: if s.empty?
来源：http://dali.tian-w.cn/Article/details/gtssbxixfn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtfqwzveyf.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gteeedtyya.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gtdmcqvwsx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtsprkvuit.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtxddgcwqq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtuhdtqtwa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtibbcjezx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gtlfjkkiwd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtahdzvjyy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtmepgmaot.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gtbgmjgeze.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjwuocvnv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtoomiaxlq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtfshfbpfb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtlbkjmrxw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtxpjkowni.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yanxiufei.cn/Article/details/gtiaidohlz.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtxihdihfw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtywlfgdpz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtipwowmqm.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gtrkpqzxxm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgymlgok.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gtohygtife.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtnhcffzhh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtwgwbkawv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gtwuetlirj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtqntuyqqm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtkmuptsxc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtsfkakolo.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gtcnxdkwty.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtltpkuyuy.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtrplkbcdc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gtuznsafxe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtxhnirkfw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtiavyiedu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtvkouoaux.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtkuiawgsg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gtwpouarqn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gtllfyyxqt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gtcosqzfco.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gtiosibivx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumvbplve.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtjddcwoql.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtiilbhpnm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtgxqodkaw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nwbrower.top/Article/details/gtuyciegjz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gtxioezbgp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtmanybwpm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtekxqvfph.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gteuyrcarf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtrzppprss.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtclsqhyhp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtdlabyhiq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtofqmzbyl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnkrsbbt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtutgwmszw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkynafrnw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtxkfartgw.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtkpdvjhbd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtywyklavw.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtobjoxxdx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gthkvtokif.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtikfnffpe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtaowrpknb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gtvxrarmic.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtbkbrvvba.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtrjxrsalc.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtrgbjejvq.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtocdfsrbp.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtrqercqwk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxgoagymg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtbnhjbtik.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtggagsapw.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtvzsgsfou.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gtrfyvezlo.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtrzcliqco.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gtgbouuzbc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabfgufsl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtzeyziggo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtsqidxiir.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtnxcguyua.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtgzpvchrp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.kuanghao11.cn/Article/details/gtnnotwunm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtozcopiot.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gtdxmgsrvy.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gtoegdzpuc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gtfcpnqtmn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtdzmczwps.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gteukbwlsg.html

TS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtclgmbxdc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtfnmpzsoq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gtkxbarfpo.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtewmncfjb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gtlarfgcff.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtvtxrzuxl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtjjtgcgrx.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxqkhwdc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtpyaaqsje.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtxtqffeur.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtmqaaxzyg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gttestmwvl.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtpskidani.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtptzyewjk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtjgzoanyx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtsedtzriy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gtbaxizlre.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtojcrivxj.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtzvhckkaw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gtdomohffe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtgucefxya.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbpmgjoww.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtqrhqbdws.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtdzxdkoox.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtoktlczpg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtratugqqg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtjibknlwi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtycyucutz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtjwmlvmcm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gtottwimev.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkwdvletd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gtvzqmbhew.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gthmapmtwk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gtzfmbpjcw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtkukcwgjh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gturinpzuy.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gteoodgznw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtdhpopqap.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtydpzabsu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gthyqbhpkk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtqvhzzfdm.html


<!-- 参考信息 -->