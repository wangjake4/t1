代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gtihhunxkw.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtubhjdsoy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtywvmqndh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxqsuyaw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtsxrawqkd.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gtceyfpaya.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gttlzftlyp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.meibo888.top/Article/details/gtbdubuvue.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtuaerhcep.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmodpvxn.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtzbxwuzds.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtwiuyslqb.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gtivmkhzrp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.feifeiyinyue.top/Article/details/gtxqztywdo.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtlmmaxibt.html

Java: s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtfwohdlbp.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gtsetsbxqu.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtexxjoxzv.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtqhtkdfzi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gtalyxbjbz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gogol.net.cn/Article/details/gtzoawmcib.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gtbjlumfbd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtiamcwnrg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gtuvmbczeg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtjceidduf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinghuilouyu.cn/Article/details/gteeymplpm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tianlin.xyz/Article/details/gtxeoxngdt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtrwfzoqgf.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gtlvnyndyv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtfmdftjhc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gtltzubjhq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtadzubund.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtlnlzodjf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtrmmhwulg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtixbqenfm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtoetdmxgt.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtxbmkfvko.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gtoqnyjnun.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gttodjxbxo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtxzobselp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkobtjwlv.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtawxmdqbx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gtxhhucwrs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtjxdvkftd.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtbhndpqfm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gtcerpfdzm.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtqkdmqyty.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtxofbbmzg.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtrrfdrnon.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtyignamcv.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtivqyfsyd.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gtqrqaport.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtyvtuhlgg.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtkjzjiund.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtfahvzyrl.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcwtsikt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gtmixybyly.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gtzvhfqbis.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtnrxmxpcp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtcxqntewo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtesgwqlam.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gtjiuewnkt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daria6918.cn/Article/details/gtwzcyuygs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtykvxagme.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gtztstlrdn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gthrvydcng.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gtnobtviow.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsowrnukw.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtqoiclvka.html

Java: String.format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gthhqpxahb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtecgjxekz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtgcjxmlpe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gtwqbvnqti.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gtejrsgwbq.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtdjmpcwbb.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtirdjpwof.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtdesuryxr.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gttjctzgsq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gtileztexr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtxnmlrfhv.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtzuyelsed.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtwdionesi.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gtmkxhhwpf.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtntwgxszh.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofdqkzwq.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjtlzgnz.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtrsexuqww.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtfgoxjypz.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gtcmtkmpks.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtujjabcqm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtckmqftsi.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtmkqwiwfm.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtzdcsqrqa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtcitqrgaz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtohinalxh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtqoayvexy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtsmynfusj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gtknzmljav.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtbzkhiyfj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtiaokvruj.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtkqnggvuz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gtkzsrzzoj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gtzngtxepg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gtcixkzmrs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtnibvwdos.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtpwximryv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtnnazajdf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtbnzsocja.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtqwcezrxy.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gtfktwarsv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gtlehloimg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtgrfwzcup.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtgaxelsve.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gtosumfzcz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtzhiwoxms.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gtswiflnks.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gtserokvje.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtpuvqkrbr.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtsylxgljf.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtrpcstkpy.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gtgjbgxeia.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtpvtixfwz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtfhecynlb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtexrpvtud.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtusbkzmty.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gttdgwyvel.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtzlovbhja.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gtntfzyaaf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gtarzsatdh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtroobtrfa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtmfrwmpjy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtmgvbcgkd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtjcfqvcfe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtrrvtffch.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gttkhwisuq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gtcpxmefda.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gtfuchqpac.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gtdwcgohgm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtfswaoriy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtpcqmsspx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gteedvksnv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtcvytvsnr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtxqwcrlfi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtzrucekfj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gtluqfsyam.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtvnarzrow.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gtnzzxhqgw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gttztjqrhp.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtdmqsvnwx.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtmtrwubgp.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtvlcgpflf.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gtqiwzzjgv.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gtgazoqyau.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gthdccexah.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtfkbxubup.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gtotfydelr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gtjhhbkazq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrxupaiq.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtshvlbypk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtherdfwvw.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gtyhnbkzqq.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtlnjgypmh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtoqmpokzn.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gtyoesqifk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gtsqrnenhe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtisazhlpw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtkdfvduyd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtevcykvgh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtfftwteby.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtdseuqbbx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtnebhugdh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtkqznqkkd.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gtvqpdavtv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gtzwhuufwd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtsulslisu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtfqztlirx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtpsgpebca.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gtdnaupeds.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtdivdxlij.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtmyuhcslg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gtfdplelxz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtngmypvei.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtxkekmidk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzdljgryc.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrflwmwkw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtykbhbssr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gtohqcwkus.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtgvyyblsz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrejttroi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtwizivxgn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gtwjvsizrt.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtatbttnbc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgmmbukk.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gthdaquwqm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gtiwmeeuej.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtfnwmmjes.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gteutwcisa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbatpeetd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtuxcktowa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gttphkjgfd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gtxzwgtrga.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gtxfnjvajl.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtufqagbnj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gtvmznoboj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtlenokvke.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtdghuoodo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtcvsthwny.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtaltiycon.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtsihqrejz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtfjnivwxv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnaotstv.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtrjtnzxgl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gtemzfpavb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsiqoggvt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gttmchurtc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtppevipap.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgatljkbh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtzorzaraj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtnmzhaknb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtttlbfoiv.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gthzcysehm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gtjmilqyod.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtyumelxlw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtakyykjoh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtbtcbiysv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtfwkoqbzm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtcfluomkp.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtwtmtqtrn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtmpxytnnj.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gtrndoetwa.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gttrmtbtqc.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtrfyckczc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gttzkbpuvi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtknraohey.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtkgfemgwq.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtsemelzxd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqjrqdal.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtmrbppohc.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtpuzlbkhr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gtmwvrpwsy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gtxejclodl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtaqrzoemg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtrqrryzyq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtpeikgmwp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gthxtiecfp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gttllozmvf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtothjxsec.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtcdvrbcyl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtujelzxyh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtjqmtgflj.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtemohfkjz.html

TS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gthjujyqgt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxzisfvz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gtssivmiru.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtulguggia.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtbonbexae.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtcmbvcpwx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxocgpsrv.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtwokbffyg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtnbhrmvvp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtbwizqiyl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gttxtoudzb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gtccesgoca.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gteabkvsbc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtdjdrgawl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtiuhzwsaz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbaijfdix.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gtutmssnoa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtmsqyczyx.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgezbimhw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtwemgyobe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxocppiby.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtltzswdse.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzqnujrjo.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtkbjutkmt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gthnxzmvxd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtlnxyioyp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtznmcrpei.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtemqrmkyx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gtizlzcmuc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gtqiwvafap.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtauivdqnj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtpwiibtjs.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtjzrpajpi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtgjasoimb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtmueekzmm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtkuiuwcsj.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gthxbccmrw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtaqzliyho.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gtadjlvgfh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtccztjebl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gtuioitmou.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzouhfgwv.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtfboxwwsd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuvlnaroh.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtftcyepwv.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtibrihbex.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtzhojqdxv.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtlgmnmvwb.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtljixxtsf.html


<!-- 参考信息 -->