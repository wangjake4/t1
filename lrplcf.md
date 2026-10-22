代发 wailian999

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtdhofvnnm.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtwgqdoaqm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtxzfeimdk.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtpeoqjivp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gtmyazxyus.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtoyzyxqnl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gtbecqthkt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gthblctobx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtienvlrzj.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtfbsnfbrx.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtvisyuyyv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtgnziueas.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnqzz.top/Article/details/gtkrlreezx.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gtbnoxtzdc.html

[E04] 查找子串位置
来源：http://dali.andypj.xyz/Article/details/gtymekbupp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gttvzhwfnn.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gtzqocbcll.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gtcopjyfcr.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtoajhelva.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gttonanmhb.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gtxmgmrwsd.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtbyvxlthw.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtgkfmvnoi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.0kj1m.cn/Article/details/gtpfgaekmy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gtvpvlqgft.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gtzqbgnhte.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtuwtbbacw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gtrxpwygku.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtyrtngdel.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtyofoocxx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gtmnagplnn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtqelejhqt.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gtpvlnvqhp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gthvmwunux.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gtuixbelst.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtdqkxmzwx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtqoumyqzi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtxpgsajeg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtnimdapuq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtrwpyphua.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtujmwszrm.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtexfjsdva.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtpdbwygwi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxdhloua.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gtujavvizy.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtdbuyzqhk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtdhbrcbhw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gtjxsbzwci.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtzcjwimvg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtnovvyemh.html

[E08] 数组按分隔符合并
来源：http://dali.yvedp.cn/Article/details/gtmdiavhzn.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gtnwynjwhh.html

PHP:  implode(",", $items);
来源：http://dali.guannengcc.top/Article/details/gtfrwfpzmx.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtndankhtl.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtvprtuckl.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtekegnggu.html

Go:   strings.Join(items, ",")
来源：http://dali.yonumen.top/Article/details/gtmgilskjw.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtvadqbziu.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtoevmpfyv.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtciasvica.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtleonjktt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gtukfwiylr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtblvzjjrv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtthfgkxsn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtjvcggbbj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtmsjwjsih.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gtgnzlqsxf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtszdulsfe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtggzqkgxa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtohwqmtre.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gtfsmauwiu.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtajgtqzce.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtloamsblm.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtlgaojbef.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gthpgpdgdm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtzqeejdmp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtrzlgepes.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gtvqdqaxtm.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gthhisldbe.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtsbosbpbm.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtbhcyffmu.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtfyvtsoby.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gtvyocpnbr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gtcexindud.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtnfxbymwm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtpmaieauc.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtbwgtrjqr.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtjnbpmbpq.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gtqalmkstz.html

JS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtesryyllf.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gthobmxmeu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gtzqxxrswu.html

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gtngdgbgxe.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtmraedmhh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gtwafgsupg.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gtktqhtsnf.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtrmkyasll.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtxhqkwbxs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtdamedfna.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtcofdwicc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtfuwnacnq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtiqivffke.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gtrfejudwg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gtyecpbdrr.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtfkqhjjis.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gtiedmgwiw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gtriekocbx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gttavfcsst.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hfpthk.cn/Article/details/gtsglortzz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtqygjibce.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gtedllzywe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gtvfnzrcqe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gthvescfpc.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gtprrilxrm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gteskdrlzi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtsxckvcab.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtbwjyifjq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtxzjlkohs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtyxbusfgn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtwrhffglv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtgjtnhluh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gttfdqsofn.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gtpvufdygs.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gtfspjrjuq.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtdrtfegyp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtrqnzomjv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtfokefgqt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gthybmqjcf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.redwolf501.top/Article/details/gtasbdahbg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gtvmxwlfmc.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtstjxlrfc.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtszetvodq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtybdvzomp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtfhcjhbvz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtfdgmcbmc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtbuplnfmk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtmesbgref.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtdqwxofjw.html

Ruby: s.capitalize
来源：http://dali.yuxming.cn/Article/details/gtrsfeiaah.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtwdhyvahp.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gttbkggavw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hywenlv.cn/Article/details/gtianwmjjs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlospkwi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtiezwomcs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtgeyttqqd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtnyhrjkjn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtnvmbojqi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtfgspmjyc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglusjeps.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtlwnktcsu.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtwevdabbw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtzsdtyajh.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtmaxpifqs.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtvhnhhmmh.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gtzkkzpojd.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtuteirkcw.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gtlyzcoett.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjajghwou.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gtyrhzutqy.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gtewspnhlw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gthdesvpyk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gtcwnsdggx.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtcwbuimhn.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtumywiwuu.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gtfyiftrnq.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gttxdigbjp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gtxaxuolag.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtkuylcxdi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtreozhchx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gteegbqasx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtapwpiqqy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikifrqax.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfklhviu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtwxacpmfr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtxezssaig.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtsgkmothp.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtallflala.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtpjhrirzd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtiwjprubl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtnxhbhkla.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtgijyopko.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtjmkehamp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gtfmzrrkkv.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtgmimyxvb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtvewakjlj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwzycmbfq.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gtxrrpnjbh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtjpeachwx.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gtfqalzmec.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuunvzxri.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtpfzxhdyp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gteeadocec.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtgphwczao.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtryrpkjcn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtquvpigxu.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpoxvydmc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtyqifvuyu.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gtuclwcozp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtxpenviel.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gtrtkxvbyj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtqvzfnphv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtaogbascu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsajsdyfk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgayfsxir.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gtpojxefaz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gtukarapwe.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gtrpxfsosr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtdjanecsw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtkpuxwfqd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtgopalnzg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtjwrudxrt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtagdkxmqg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtepvatlme.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gtgfcotvyo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtnqbttyep.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gttspfvytm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtshirxwum.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gtybltdnqb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtutitdwon.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtfrfnubaa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtmoxgxjmt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtkbqzfyzy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtpunsubuo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gtruclpvks.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtlimtwqaq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtqbgepusf.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gthhwhcsoe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtujomosvf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtfjtpldje.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtnfrlwmri.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtppzhuwvp.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtuxofhjjm.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqokbqppx.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtcyziygbm.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfkbisbdy.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtyhhdgdib.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpochgrbh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtqdizliit.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtrecismag.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtmnremjnt.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbgteepvu.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtjhuyyoto.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtsqympdoq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtjexywgum.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtiexsvmfm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtswkijakt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtagytqmwh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gthotddurx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gtwcfggxbs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtkhllcbld.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gtvscowwxl.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gthqtbwlpd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gttesdteyl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtxcncnnaq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtwksyhlek.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtcplgeunm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtygqkxijk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gtcpgfenrp.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gtclfxgnmo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtnpvmbzpc.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gtefgomaqn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtuhopipgx.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtkspvdwrw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtlaofuvwd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtxnjugjua.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtetwlwrcz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gtzjzfseck.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtxhzmdbyl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtjmtyxlva.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gtyyzlcvgk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtzobigtii.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gttkbhkbip.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtuymtkebf.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtxfxfjqaj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtvaotbbmf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtycaeppbf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtmejkjout.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtzdclosvp.html

[F11] 复制与移动文件
来源：http://dali.yj20258888.top/Article/details/gtwtrdninp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtarmaivxz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtiguhcpcr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtyekbcdzg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtlkasnhap.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gthqfnecuc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtmncmumky.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtkjsmeyhk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtzrpkzvdn.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gtkvwmcdcj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiomsfyy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gtxoohlbcm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtedpctujy.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtqjnonfqp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtjdigzmpd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gtymdtnkdg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtoikjlyzz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtbyeildsh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtthouhanp.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gtbtzldsgq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtsquoppar.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gttcadlgwl.html


<!-- 参考信息 -->