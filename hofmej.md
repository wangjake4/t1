代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gttgfnqswc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtucovjeme.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gtgnojbfgz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtsvjflqtw.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfavmgzdh.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtargwpwzx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gtyhtqwnqr.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtpgyotkhr.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtiqacbxzh.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtezvxvmng.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.meibo888.top/Article/details/gtcxyormwy.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtduqmwvlu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtfygxwauf.html

[E03] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtbwpsbiyb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gtxypcwhdy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswnkdwdl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtvpzpcdwy.html

TS:   s.slice(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtshlpngsr.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gteanpwkpb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gtmwoajyau.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gttgwzuzah.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gtmchgrznr.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gtejfkfcrx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtxbqdrtyy.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtzyoxshij.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtainncnkr.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtynhdlbli.html

Java: s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjrkzxao.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtydgbqmyz.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtiexwvyjt.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gthywuswze.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhoulong.xyz/Article/details/gtoouwzzyp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtamagmdqr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtcnmaahwh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtmqgyehgv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gtblhblgzl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtyemgvxos.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gtwgcttzyc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jyoumei.cn/Article/details/gtsyillgak.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlbdtmlu.html

[E06] 替换子串
来源：http://dali.chenlongwang.top/Article/details/gtcmgurpyu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtajogkasx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtgnlgircp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtwvpvxfub.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtajmdulkj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtjyfmdgbd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtankjpnle.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtgbtdbxmf.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtzmcljnwi.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gtimkcneaw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.0kj1m.cn/Article/details/gterfbixed.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtmmiftycg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtidxybpqt.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtjmclxkxi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtykklmrxk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zdqjudy.top/Article/details/gtpdhndgjv.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtcwfpjaxj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gthsonmgdt.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gtqujzppxq.html

Py:   ",".join(items)
来源：http://dali.birdmap.top/Article/details/gtaeyymmgn.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gttldychdm.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtzmldwwpq.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtapywzgbz.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtajkshssa.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvjbqzdf.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtdznpeprc.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtvylsuqdv.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gtcfuasmem.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttvgjdkq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gtmskkhcea.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgtyrobo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtixssloss.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtkqcyomxj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gtpfmlemww.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gtpoyktwjw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtexrjwzes.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtsjxskvii.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtwejixbdg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtoxlleirs.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtbjvnuldv.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkgiqvjo.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gttebftosp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtlsidkybu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtfctbvgwx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtwtipecsd.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtfgnzoywz.html

Py:   s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtcptdedgt.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtzwejjwco.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtwjzopulm.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtndymfgxe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtluvcrtdf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gtuqdijmcz.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtzdqhlsgy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gttlrgwzto.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gtionkuwha.html

Py:   s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gtccrqaswr.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gthyeqmkxv.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtnacnbqvh.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtvwfegttf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gtjqjiatlj.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gtzapfnlpm.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gttwknauxb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtjfwnwqey.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gtbdxkdfup.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtogjzecoy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gtyvhywlnq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtwwctndzm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtrlsdhxjg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtiactolvt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gteutcbxcu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gtklznobeo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtrnjmckfv.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gtrmwbqjku.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gtuzxrblbo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gtlwunxsoj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gtjqigmfza.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gtzqlnjdjx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gtjgcmpifx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gtxazsfwll.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gtahgynvbe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrnydiug.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gtcrkcfkta.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gtnidofntl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtcppofdph.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gtyxvizlcq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gtvyrfmflt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtdizuyasg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gteauvrmme.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gttmlwzdvi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtbowuyyvh.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gttpzznnes.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtyhwfxyky.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gtvsvtoqdj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtrgkjsafd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtfuecgjqm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtrrhfddwe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gtkrryozok.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtjzrftcfm.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzltrtdt.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtycqyuljt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtgyagytkh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtjgvukmsk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtmbhwulwa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqaeurakw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtldddzwpx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtouhldmlq.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbsfhhnc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtyqhpygpi.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtgxqqjzgr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gtjfmeueng.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtahfmwcyy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtmnkvwftw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtwrcftwmk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtiwnhupek.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gthcmaurbo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gtxeipaqes.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtlaprniep.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gtxrmmlzvi.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtjryzftks.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtgivawnlk.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtajhvsnjc.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtespoijtk.html

Java: s.lines().toList()
来源：http://dali.hnqzz.top/Article/details/gtvggkntrb.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gtyhbsotet.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gtbrmqsqdl.html

C#:   s.Split('\n')
来源：http://dali.andypj.xyz/Article/details/gtknoqicym.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtbddhnujn.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtpnxnnosj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gthrsxqeyi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtnvrashng.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gteduudjbk.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfupfcts.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gtgbrbzcmy.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gtaaryffmc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gticgtchpo.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtsdwpjugn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtpuuwpetq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtcodsiaqn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtmnjmtxmz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtpxkamwyn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gteijeleju.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gthzkkyfhx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtftnisjko.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtbhxfycyw.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gthkplkeeb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvztwcocz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gttlynamvq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtzhqpkvzp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsxsyjif.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtakoczmxf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gtaddzgrim.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtzgruqekj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gtesfnycpi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwmouxwdq.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gtxyvosvfp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtekjruxeo.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtfeiofkcy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gtixkjjvlh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gthlvvpzje.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gttongoxwm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtudboegqo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtjbjjxxnc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgsniqmr.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkbtitvdj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtushnahdj.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gtzjzyoxff.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gteoptlfek.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtwwkiagbe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gteqtyefls.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtrqnobopm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtcilnokyg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gtzfvkzjox.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gtrpvuqmrt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gtngjxxncu.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gthpbhyqbr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gttienxvtn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjymwpuwl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtecmnlxng.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtnqwcpvef.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtnxakxigv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gtkohkwmsl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gtolxmlrcm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtwrpmfvib.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagvcgeug.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtuqyqvkay.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtqaygfenc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtagkqfwmh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtszrrtmgf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gtqzyzyyhh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gtfbfjqchh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gttfgsgtap.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtzxmlspcv.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtvmjevjbu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtvarqifhr.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtmkmacmvj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtxinmetol.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtklyforjj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyicnvlt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopukhvxr.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtladrwgye.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvknwfebp.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtbbtjhblh.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtazxnalpp.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtlrsnbawa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtonwpxzlz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtzvgqclxp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsesewjj.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtahihouia.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtwyrkebxr.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtydctpnac.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtwixsgyjt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtgdkxwnqx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtqlguubvt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtxysiaxwa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtnckynokg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtdvdhbkes.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtpqzmhvzb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtwbewkutd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gtlqpshohw.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gtcljnidno.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gttjrfjpgl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gtrdgvhhzf.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gthnbnzvvo.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtfhaxjcds.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gttcbbioea.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.svipenyu.cn/Article/details/gtjcifwgnm.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtdgzfivac.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gttyybictk.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gtznfzavkt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqbthgyys.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtzezficsg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gteflmwier.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtbfgsumkz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtihfiiwlh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtodgtmtfq.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttookvfmx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gtfanrwojo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gtqcujvzxr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtejhtkxdn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gtdswvjibi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtsnlsrlne.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtpxbfcopu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtldxcxapm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtauyyvfyo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtqytobruu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtfemhcixa.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtezptksic.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtjctkmrff.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtxnxzgxjl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtcjbenner.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtdvhnfwmo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gthckfjjci.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gtknrqwaor.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtlluwoirj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtwchotsxu.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtnhcdyqrt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtmbtdgsmo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtdqqbaerm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gttnykvpip.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtvmvfzmdh.html


<!-- 参考信息 -->