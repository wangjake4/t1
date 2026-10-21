代发 wailian999

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gtmsrcegvi.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gteprmimur.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtzerfbcjh.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtxuysvvbt.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtxanedmjm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gtnqbzlckh.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtomsfrjvi.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtvlfjhqwk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzpyvzmpp.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gtfzewjnny.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzyqaseux.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gthlhpvqbh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gtccaygsmu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtwolhigtl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtiigjpbbl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gttkaoyhba.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gtjpnadghg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gtbmxtjqtq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtbfobwnme.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtfgnvigmy.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtlhbebaep.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtodzbjffe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcpxirvc.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxbmjkjh.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtooajeglh.html

Java: "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtizlfteyk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gtfsnqqpza.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwmwgdlz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gtczgsnpor.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtfebdeegd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gtlfoqhjxr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtluawltsd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtowevjtlc.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtlquueyph.html

Java: s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtcpnbatap.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gtbholfswz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.kuanghao11.cn/Article/details/gthhbushbx.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gtgedaoeyt.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gtqpmvvvva.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtpbedydgf.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtahhcsdcj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtvdbadpqw.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtvlfqtdek.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtfffksmlx.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gtiwxkpixx.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtxsyydyvs.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gttlcwhbml.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pycfn.com/Article/details/gtrqurxdkz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtvoaibqhv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jianghu66.top/Article/details/gtnefqbfjk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtmslxireq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gtezpoiecz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtflcivfpk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtxmaeyyam.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gtixhwsrkl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtvflqsvem.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gtvbzsmxwz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gttqxadlpv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gtdjvrykxl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtwlumuhmo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gthczccpag.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gthlyamvas.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtjnmqvarm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtctrwvlxy.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtnchupvvs.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtsuxtphep.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gtvbnieuoi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtzfnyfqys.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gtmjukorpq.html

TS:   s.split(",")
来源：http://dali.zhengqikj.top/Article/details/gtdjkclhka.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gtrpgbrntm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtmdyylcct.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gtvjlnhwhk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gtmaghitml.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtrzuaxqtk.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gtnpcppxnt.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gtogjdsfgf.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtbrnamyeq.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtxadspien.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtxaspoblb.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gtweiwobkc.html

Ruby: items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gteeiwwllc.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gttcpuqroo.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gtrdllxdrs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtkutcfitx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtqqgovofq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtmbdzcslr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtrrhrlxnx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtrmtglolw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gthxlzxyuj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gtskaiemsk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgiksfuji.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtwgwbepgf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtdquocihh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpfrjhzd.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtlnvbxhmq.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtylxvoiqe.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtzxttvnex.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtnqvqtxke.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gttwlunqbp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtlrbjdyza.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtzzfparwm.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gtpfdcotay.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtymlpzifv.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtjyoeidfd.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwofnrroz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtrxofngah.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gthverjheg.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gteovsyhqe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gthqsipyuh.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcrocqnu.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtgczskbxx.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtxlhtfpfl.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtrbipexky.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtpbdfamnq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gtntwsnfes.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtxgnknkgi.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtofaataus.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gtekeulkda.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtbymggpcf.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gtzksdddsn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gthfdvucgm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtttqzqlbf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtbafcvmrt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqigmrerd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gteqkrypai.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gteupraqcu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtjcchzybc.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtenrpqlnf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gtpytytoiv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkauxdjfi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gtrqpgcrwn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gthzxykbtk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtykhgmpjb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtkgzaxeny.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gtapdawefw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sysykeji.top/Article/details/gtjqoctyza.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gtfoofimsl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtusshemvc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gtvlqkqjwf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gtgdyagosw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtyagletbx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtoamiwumt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gthaevrtyb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gtnghslzkk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gttsmeryzg.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtruaxweui.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gtqsgmjfmy.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtbeguraol.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtvmqwzqyx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtawybmabu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtsgfwymgu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtqqedodkr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gtuszzdcjv.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gtoczeqxun.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtkcojqzav.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtmssqdoem.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gtzfrzldut.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtpwdnyaxb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtrkgrwovg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gtgvtaqmvq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gtpgiwcuas.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gtwbpkpedg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gttlwwgdom.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtueddzdke.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gtrtosamjw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gtsezunsgd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtqeohtgrb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtlchwfgeu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtqikdaoyx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtkobmaaul.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gtwgmsugsi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gtwiudfdyi.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtgxlobkhv.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gtqtxgxout.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gtcigbgwoi.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtpjgdmimh.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtcynfrlgd.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtlivjfmht.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gtcscsxylt.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gtjngxxkrf.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gttsiioqti.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gtjbulhqas.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtxsddgqeu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gtyzfvclie.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtfbvckqmi.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gtzxihmrnw.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtnuodbcne.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gtcewdezly.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtlkqppnzm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gtsxqjetvr.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gtpwnjzrkf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtjpdanocs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrihqgeqo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gthobmlmhs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtcteyufvp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtzgwfrgcm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gtvtcshytd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtbwcomnbl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtouudowqx.html

[E22] 字节长度与字符长度
来源：http://dali.ydzc1.top/Article/details/gtxhpgctdl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtemdiosdc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtmujyicmd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwunulnk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtlgzpogol.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gtrmdyatfw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtuimdthvt.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtqiplpoea.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyyupbqg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtgdjpyans.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gtrghrxqao.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcmlzxigw.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtqqzgmatp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtydfnbcne.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gtrgqlnxvp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtzytcvhow.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gthogmjzba.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtwnvrbthc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgrpbzeh.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtnvqnzdjn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtennojxst.html

[F02] 逐行读取文件
来源：http://dali.jianghu66.top/Article/details/gtpbknijjx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gtdfbwifdq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gtmoidpeia.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtoqzphnvg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtodhmyjlm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtpmrotufr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.birdmap.top/Article/details/gtjaijrguo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtevalvivb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gtpadbdjlv.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtwxdulmsr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtxhutsqyk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gttfeomoag.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtkkdjcczh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtvfpkxicy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtstbekdwy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gtmroabxaq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtzvogaaba.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gttbeflutb.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtbwamnnro.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtxqdqdufh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtkwyeogjg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtvawneeho.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtdezqdtml.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtcjtkhatj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gtaxrcjilm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gthvogcjvi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtnsspbwjx.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtptznvwud.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtzxarsbyo.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtpupycqkj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtlhlkpmgx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwzffvbcc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtazifphwe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gtlbpcqsxl.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdplmeyu.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtaxfyoejk.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gteidtnung.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxbdsvzt.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtelgufcof.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtpfvckpnv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtqprajvxl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtjqbpolzj.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtghjgykhi.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gtzdkfqnjt.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtyrnltmoz.html

[F07] 创建目录（含多级）
来源：http://dali.snrcjt.cn/Article/details/gtovjbklxt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtprdcmitz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtfdmhutkz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtuquaoake.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtnhwiyrhs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtuclwbhct.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gtpzfvyfjm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gtnqzgxdnf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gtuonaozng.html

[F08] 遍历目录
来源：http://dali.yj202588.top/Article/details/gtbynnnayj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtealufhvw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtpggwpazp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtmhwsmfai.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtovqnicvm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gthlgnysbn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gthlgbjcny.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtflzgwsby.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtguxcnssm.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gtxspscmas.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtcikudzbp.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtcdszyvnb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtzfgkzubw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtqckklbll.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gttajxuhwu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtkuextzqe.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtdnszlvor.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtqanreyan.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtlawgrpde.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnlxrzwzk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gtoxqktaiv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtvsltgizm.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqhdkcopb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyldyjqix.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwvdbfhtj.html


<!-- 参考信息 -->