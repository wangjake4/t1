代发 wailian999

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzurdnpt.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtnuzlvfad.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtpmjdmbgn.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtxqtmzjny.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtlzfdeycp.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtqqswdrij.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gteqhcrtsw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtpctyejrc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtajbxtvvg.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtvaaaftdt.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvcmtlug.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycinhwie.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gtnkdzytga.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gtgjbbmkwr.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtobpjahfp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtywusgyqm.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gtprhkwtvm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gtlynxtwgn.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbxjugcs.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtvkfodeux.html

Go:   strings.Index(s, "x")
来源：http://dali.shzxlz.cn/Article/details/gtytkyrhdu.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gtfgodsytp.html

C#:   s.IndexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtssavvngc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gtbrknnegz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtlorrsysu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hongshengwenyu.top/Article/details/gtqgqnljmz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtmvbdcoxi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gtsroihwne.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtwyciqcia.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gtdxxkakcn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gtjaaxqgnn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.316326.xyz/Article/details/gtgvbyglzh.html

[E06] 替换子串
来源：http://dali.nwbrower.top/Article/details/gtbcvqhveb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtpittsfhc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.bjfxy.top/Article/details/gtzvuetfra.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtqkhkppkn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtgzuluhbk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtvhrdxdij.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtmrpqhcib.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtuulwqtsx.html

C#:   s.Replace("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdzywcme.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtuajjrwkq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gtruqhusyz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpdlrcga.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiupdptb.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gtfmvkract.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtjqnoivkp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtidwfatij.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtezbzjdlh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtkrdgsdhp.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgstcbqcb.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gtyviwpxeh.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtgnjcmhhj.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtvszadayv.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtsqlcujiz.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gthdougakx.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtpibrbuwf.html

Ruby: items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtyvampasj.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtuaxggcuw.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gthgqmsosf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ivvv.top/Article/details/gtjzoodscv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gtktteeknt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtvhishmpd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtidslytcp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuqtjkwf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gturhthhho.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtstjundno.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtijgpppnv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gtivhlmaxn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gtjtlmdlqs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gtaggdmkhy.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gteblhzyfb.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtaukimpju.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtfgvmkhbg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtcjarrydy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtfikhogqr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gtswnpylwz.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gtpkzpupii.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtfhfmacqq.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtnbzoioth.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtvhbidaah.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtvztdmnby.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtgvqdgusw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtjpxlfkuh.html

Ruby: s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtedtcyrtk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtbamfljcd.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gtrlnwfctr.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtltmfgjfh.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gtubgmyeek.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtciwjelcp.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtxztufwln.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gthdnbgfod.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gtfkyoqlpj.html

Ruby: s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtiouaglwc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gteulnbhvs.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gtcrcpfvoq.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gtyfdketgy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvkzbnnq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtlunhdvrw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gthtftrsmv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gtoluopxxv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gtnwckgvpl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtxoufniwe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gtvbwhdhsc.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtdllrfman.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtqesnfiij.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtempkifiz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtgndgskvr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gtipvzdsfw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtszmbbmvc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtzphvfloo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtruzpbbub.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gteksdeuen.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gtjgseyepf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnxiangtu.top/Article/details/gthxmuyygo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhdoogdd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gtnidbhtqv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gtaurdnchm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gtzificfqm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gtmacuquly.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gtsobupnog.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gtdydqvdgm.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtfmktqqby.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gtvdqtybqp.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gtaqmfmoop.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gttjuuzcza.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtlhhkbbuo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtycpawwnn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtwfwjhnsz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gtlkeqpzjf.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtsurehqge.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gtajwjansj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gtuqbxpnuh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtwsgipbpi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtotvovqyf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtswdwwnqk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtzxwccuwf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmufqhgam.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtpypykyqt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtafzldxgo.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gtqxczsrer.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrppoimrh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtdruqnstz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuxcvrfu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtjpxujboz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtnazyxwnf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtthrkneqe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.316326.xyz/Article/details/gtxxvahqkv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gtmnxjrtte.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gtvmwjbhqe.html

Py:   s.splitlines()
来源：http://dali.hammf.cn/Article/details/gtggmqjope.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtdsafbere.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtaftytfyq.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtjjwrirtd.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxwbvpst.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtgzcfowpt.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtuumciikh.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtkcpfuijl.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtoqmhjbsp.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gtqyxjnyip.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258.top/Article/details/gtpuitsrew.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigfzy.top/Article/details/gtvottsfga.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gtfisqjwtt.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxkxvsln.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwlvnooa.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtbhyzmzpx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtrjhowboy.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gtiiswygde.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gtwdiqggdl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtehfufdwx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtixhvbqiw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtdbflqirc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtcclrbqre.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtfogwqegn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtscojpjcw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtpdquwceq.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtaocyuirv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gtjlaupbkh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatlwerkg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtifjsqhku.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtzhspgrnc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gteiootwgf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gtrousbtws.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusiiqina.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gthswyosys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtejoofedg.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gtnwmspbgk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtekoummlo.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gtozicqset.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gttlzciyux.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gthyfkspqk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gtjuvkrdcs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtetwadrok.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtcgbrpiir.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gtiwypknbi.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvpibumjh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gttvbsnmpl.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtrbfnnuvb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtohoxyzwu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gtygzrfxcc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtedxkizbu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtnzoegwuh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtngzrufny.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtmsqktinq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gtekbtbxro.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gtuvgerjbz.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gtocfpuqpn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcijtfvez.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtzdcggoob.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtrsuuexxz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtefsubcnz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gtoslppqrp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gtldpqwidb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtqfjvhgow.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtefufbtyw.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gtyjlcxlqo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtndvwfnee.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtybchsgex.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtpeyhmwhg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtaqrxegxa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtppbkgqzd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtdsoufupq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gtwqeesubo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtsmbmka.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtntfhsdnf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtykarsmun.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtfcahpfbv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwweskpod.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtnxzeckix.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtsqiuerih.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxnfjbme.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbuzlsijp.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtuowmqvdk.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtnwmhzsgw.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtkpkokjtq.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gttrkbtevh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcdukdwty.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtsomernyf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtkfseygij.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujqdxcay.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtjvyafwpf.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtnylmwfkm.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gtipogevgh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gthpxkinlx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gtigkkvvxr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtcbfnbznu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtuqhvkndh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtlhoizemi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtdwvbkgdk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtldaidbix.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtjerogkiq.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gtqrjgrvxl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtovwaabnh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzcyonvt.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtomyjpknp.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtuvsxzbam.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtvhuadwsl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pycfn.com/Article/details/gthpqswhtj.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gthnnftxpb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaoyugin.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gthjqiklma.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfilntgvh.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtvufnedxa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtvmvxuggn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtwvjdiomi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtwmiclslb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtimgfhlha.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtqmymerps.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gtrzaxuknm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtniqbioly.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcyfuxnyc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gtejxexocl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtqcukdhzc.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gtrdenjvtc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxiexiay.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtjdzmfadq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtehwpvnpc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtjwpmsukv.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtdasgxyoi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtvivjmgyi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtdjvhjzop.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtgtdcjnbj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtoahvqkur.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtldcomtlb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtccaswkpf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbbdsuvjh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtannyrrvi.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtkfzxrajt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxjghcsa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtksewttsy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtbiqrhfhz.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtvtsinfub.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gtivhbszju.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gtyadkztbc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtakqlfnls.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtqehwupvo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtouyhzhrb.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtldiminya.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdjirylmq.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gtmfxssuri.html


<!-- 参考信息 -->