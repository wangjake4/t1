代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtbwfentpo.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gttneksnne.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gteajzjogw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtytotkiop.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gtktyewipt.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gtzqoycblp.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtwmjhbnwv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtxemhzvuj.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtpafmrsmv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gtbijyyidv.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtmzzzbqre.html

Java: s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtkdwlwbib.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtxhfmgrtx.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtpcujffrh.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gthrzihgyh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xinyue.icu/Article/details/gtbetklras.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtsppwkvrr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gtuhmnksir.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtrmjskpch.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gteqqofkje.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmxvbbwg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gtellsejnm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gtcmapmrno.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtlaqsjq.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gtjjnclxri.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtvfmbrbol.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gtrcudxpzn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtzthjuufs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtxtimkjwf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtakhpxweu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gttsfvemmf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyojbjefd.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gttjlrfzle.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gtvdvqaanb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtwwjztvjt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jianghu66.top/Article/details/gtkufrevkb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gtucknccfm.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gtmspobzmz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gtcpaqtqpf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gtsdniscyk.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gtthqutkdn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gttvwqxvgj.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gtslctabrn.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gtpogjizvi.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtcuivfjwk.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtagrwmopp.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtanlzyqmi.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtoykhsyhq.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtophqqroi.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtvpierbcr.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtyvaknnku.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtcbskczvx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtyodslyte.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shuidangran.top/Article/details/gtjcnliuci.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtgpxoamvu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtrmhgtslh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtftmfpfdd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gtudsmvqxn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gtwuyzrpac.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtoskhodhp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shuidangran.top/Article/details/gtuumxfyix.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtixoeregt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gtmkubzqcu.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtvqoatyma.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtdgaqpfxx.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtagyvumli.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtpvbezfso.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtqscbxqhi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gtyyqsbcks.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gtukztnuos.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtlgmsgemt.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtrvnxqqlq.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtbvdyqvbw.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtpmfuikdz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtwjfusugt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtzmyozevd.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjihfrfei.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtmblhzgxc.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtizejxmem.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtjtkrhcvr.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gtfqcaxvlf.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtnvfqbdiu.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtlgykfzbb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtdnaqxkka.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtvvcxgprq.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtimlrnydg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtkgrwcawm.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtfcoflopb.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gtmjnhkddn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gtkuimplne.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtaawkssev.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtbfhgtpfp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gtswnnexvm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtueptqhlo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtkqvwmkib.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtafulsisc.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtisotqjua.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gtjamsqoqs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gtznmyflyj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtnftfqegw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gttnjruyyx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtuwobzjaf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtfyqobolf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtcseosbxz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtdqixwcjp.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtswyzkgeu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gtqwisgjcz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtqrhrwmrx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gtemclxnrb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtmcvtamdd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtheziwmsg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtpyanorvu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyjmqaii.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.andypj.xyz/Article/details/gtwtsjvknk.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtlaidtnha.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjibuhrz.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtfnjmznco.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtslhsuuwa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxrhnwdf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtzsxakngu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteobtutms.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zdqjudy.top/Article/details/gtjvidtytz.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtmzlfikww.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtwaksierk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtgklwrtbk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtxagwrfjk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtwebkztde.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtgwimtbhn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gthimbcupw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gtqqtyssiv.html

Ruby: s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtxvlyxprl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gtufgybhwt.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gtxsfnyvjp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtcvdeehwu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gthqqklmfu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtplrzelhn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtapcwhpwa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtnanryeat.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtxtoovsih.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuducniw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gthqraiwkd.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gtubaeyvpn.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtdpgoksuf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtgwkksgas.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqalvnkgg.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtmyohncet.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtttngwclc.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gtsiwboqxh.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gttlgmmfsk.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gttitxagte.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gtlhpjilgc.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gtqjiubwag.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtyftqabyf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtrvrhbblb.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtvtphwgah.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtgkopbblw.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gtumsaymab.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gtptaacecb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtgdkktkho.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtblfxinoc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtfedqvbpv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtddfchajc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtfzkrcqia.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtzuzmudqw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gttirvtaeo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gtdxhqecmm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtwtvtwxra.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtsmduvtfh.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtoqqvrfza.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtoztbfmtu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtjtspkrol.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtjhgriyrg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtrvnolrub.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gturwnlysj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtnohzrbst.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtaykzdegx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtjhsdmvqm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzqzzwhoq.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtwhdobcoq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwcrjluy.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtimpvlwed.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtalvucbap.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtxmvbxfkv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gtuhulzgsp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtujslbifb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gttbfvohxf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtnocylmnl.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtzrvwzzgb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtdetngnuk.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtqauagmhc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gtyhsyesyd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gthhszomlh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtajgjmzfb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtmjsvwawf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtfwvdjmvv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtoxyfnkzg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtesbejdjz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gtpdlncrac.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtbflvffuz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtrlknefyl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtjmjgpqmg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtakevmlma.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtqvvrgfjh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtaktkhtub.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrncngaa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtjwzwzpof.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtqdwkpsei.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtkhsbqkeg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gtafsbymem.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtxbtllvts.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtzhcchygj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtmisybnlm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gtqhiydzir.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtmdcpgrpw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtefqwelkv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gtdllietmh.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gttyuiorme.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gttbsteiqf.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtffyqjkwf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtqtbonprs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtovkisrli.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtwbucwpyq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.mhx1999.top/Article/details/gttyxglpjj.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttyflfpvf.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzubemmkt.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtnvnxubuc.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtqfxhlycj.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtsdhgztyo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gturuekbyp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxhrpogic.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtwjkietwc.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gticxowsjh.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtymgmgvhk.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtxskvtrwy.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtntzyshsp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gtfrravmrd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtasoslfcq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtknbxyhup.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtjaozwekd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtnqsldibg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gttgcsvgyo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gtoqzlopet.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtablnxoci.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtwwximzgg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtfrvpsnot.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtxuaawpwm.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtkjyjzqeu.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtpoqpzehx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtjoaxljai.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gtjmxkusgu.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtmgvdmanv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gttzhsdlch.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gtmenhpghz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gtxdzeskfc.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnpphoxo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtzdbspzbc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtbchepnfl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtllwvrawg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtrungxxif.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtgibgbwfu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gtunerzizq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gtxzwcasdy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gticfwfcoc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gttymjhupr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtaqhzdizj.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gthqolzcws.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtfpembayg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtdsescpfb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtbbvitdgy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvkpoqwoy.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtcwhykxyw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtwleobgar.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtyruuivty.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtbfloragh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtcftaqibd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtraytfdbs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtgwnjesmj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyuqbmht.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtrssfenut.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtpyeilzzc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtctxatnzd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gtduxxvjnl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtwoipcmxk.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtwsjgofsf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtiuseqxcz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtsvjqurrr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gtmfvowdsh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtvfodwxps.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmupyxkju.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gtpifqfdrz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzodsqldf.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtjelxryih.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtwkmwkibu.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtpblzammw.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtcytywwka.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtwyyrqezc.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtxmuitbgm.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtureuamel.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqtxdrmu.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtghkujtjy.html


<!-- 参考信息 -->