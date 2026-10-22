代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gt2ejmgogqo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gt2vmfnruro.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gt2scvxuquq.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gt2itumbzuc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gt2bdydeiin.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2hnbbjzrx.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2hpacsmkg.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gt2xymiyrjw.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2rojfyjuw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gt2oqnighfm.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2kvqcorvr.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2rayrrbqj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2snwbfoou.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gt2windngbn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2jcplfckw.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2lpwbwbdq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gt2rznfztws.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gt2qfcquaev.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkgkwbdf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2kydagsxk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2ohucaggd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ehwqpu.com/Article/details/gt2zbllmnys.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gt2undvfzuk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2gjvhssia.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gt2dqpxwrmw.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rykkaram.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2skvigdon.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gt2xtpdrgmh.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjccmlen.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2yxksmvlw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gt2csbuybnt.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2tfvjtnco.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gt2hrazfrdt.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlbbympa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvppjilq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2fsktlubc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2sxsoyzdc.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aptrsczd.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2vqiiullv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2ckshhseg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gt2hjaekxzv.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gt2pxlnfrcy.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gt2kpnzjwjr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tanke756.top/Article/details/gt2dbpsxiso.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gt2wgoiucjk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gt2hobssryg.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2flnvhgft.html

Java: s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2ccwfvjbz.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gt2abisumod.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gt2ugumfjdg.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2fwuhotct.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gt2pkzlvhqm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2zgsmcjdh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gt2eacehjad.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gt2bcoxezoo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gt2oiqmiupl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2kzafywia.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gt2iokbnswx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zummrrmk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gt2cpcxzjby.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gt2xoldmiyb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgsnpzra.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gt2yuhdjfll.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jljevxmp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2hyxfjwkx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2usktrvnw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2ofutmjpb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qigcoueq.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2psxzqdwe.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gt2gcuenhtb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jeaawzws.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2fiefxsyg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gt2sopfuaqc.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2pqdfzhux.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnmxptlm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gt2znxqigtu.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gt2ewijsmfs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkgwwrvk.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gt2magqwblc.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gt2huytaeiu.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gt2ivlkgkje.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2mcuvuruw.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2ozhifazy.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gt2nwokjmjj.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gt2rgibjoov.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2ogyxwpau.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2zjatzxyj.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcamyvvz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2whqthatb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.mhx1999.top/Article/details/gt2zvitqjau.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gt2jrizdcvz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bngumxbu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2sawrdbdi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ehwqpu.com/Article/details/gt2fxfqpkjn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gt2zblmiatc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pvlwcgvq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gt2kriyqzex.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2ydubpsfc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gt2tefsepty.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2tnvpmpiw.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2vlaixyoc.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2npjsqdpd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2bdjoaxjp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2gnloyidf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gt2oxxdsmfw.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2zgthxykz.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2pnsllgwk.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2bdzposon.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2lpwenzhs.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2turivnov.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gt2vdwhhpcf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2obamgtaq.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2bvkfqaif.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2qocoaeuj.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gt2xtethfcn.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2yfqdkcgz.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gt2nvautzfd.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2bkgwcsdj.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gt2rqrkihua.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gt2nphfwvbv.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gt2flshhvtq.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gt2nvupajvk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gt2vltjbwvx.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gt2umqboote.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gt2uwlwfrad.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gt2wpfialse.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2ctfxxhna.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2cneaojqg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2zwkxmizo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2eifkmurk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2mazdxisr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2pttlkppr.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gt2jepxbubo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gt2upznhkdb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gt2ncrlpbap.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gt2rzwzgexf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccqxjwbh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwnbtdbt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gt2ygoaehar.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gt2rinowrwv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2gmkdrkyg.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gt2gfincdwq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2gptbqufq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2sgehmqxp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gt2wdsruuwh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gt2blfaedrw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gt2owaibhuu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pocqvtqc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nholhoac.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gt2vofusyzq.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2nivozxzm.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2reltyprc.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gt2gfxnmswk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gt2kcbnnlds.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gt2texmuevy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gt2afjawxhy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gt2jtznnqzy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj202588.top/Article/details/gt2xvqssxbp.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gt2sljumiou.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gt2scfrzwml.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gt2jxnwozky.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gt2hbhdbpzz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2nvlscqrf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gt2umzzzlak.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjgxggon.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.redwolf501.top/Article/details/gt2fcixpuck.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gt2acqfuems.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gt2byhhddqy.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gt2idiostcf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gt2urwbzvnb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gt2szznbylz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2ghvywuao.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2ubkltlov.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2jintrkvi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2iiujvwvd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gt2fvyfvjwy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gt2sffdtxot.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gt2ifsuapfh.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gt2vponwwzo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2elwnmqsz.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2wfqmqoep.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gt2ieeggnlr.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gt2hbjwywdu.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gt2nknqlxll.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gt2nnddxiby.html

C#:   s.Split('\n')
来源：http://dali.yueranfly.top/Article/details/gt2schckkxa.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gt2dsrocpmm.html

Py:   if not s:
来源：http://dali.zhoulong.xyz/Article/details/gt2tgwdzfuu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gt2bujlrkuz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gt2qwvdmcqg.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gt2sxfsbpsx.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gt2ekiufmiz.html

Go:   if s == "" {}
来源：http://dali.zhongyouzk.top/Article/details/gt2itfroctz.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gt2isvapdcj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ybtsffom.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gt2hqhkwvpz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gt2esrlcpua.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2wopaiqmn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2omqbbvqr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2phlfqptp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2svoqxyjl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gt2ogwxmpyp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2hpqbdqxn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2kpizziwl.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gt2ainjenxh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gt2wxxoblge.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2uqpmkxdo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2fdiyrxmo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpuaemxx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gt2xyrawjap.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gt2ubdaqvrs.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2ckejkxfd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2dnxtvyaq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2gtwkiwww.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gt2umnztutv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2xbhgforb.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2azkoesdx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gt2hxdvhcpo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2whiwnxcy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gt2gjvxcxws.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2fivorloa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2vytwnyzk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtjierru.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2xpmlxnya.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2xhvthxxv.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gt2knuinqtg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gt2gcypydww.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dianchejie.cn/Article/details/gt2pdqjneql.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2bwnapgxm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2rhawjrvo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttyfzith.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gt2uqnhztvc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gt2jzkxdhfm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gt2gotfcqfx.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gt2eilleqsp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gt2hpmjitfg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gt2glwqoytn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2idyxarcx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2lyuvsskf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gt2urocnkiw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gt2hbvvtgsy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gt2jxwidtcr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2lmncfvba.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gt2qygmdcwu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gt2tkcsovus.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gt2kchxhxfg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2ymhsfpzd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2kfarcuab.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gt2ishwqcqy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2qtaafwee.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gt2gbtsxrlg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxpxpqes.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gt2ddwxpmqh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gt2gwfqmwsw.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2exnqzdcg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2vjqylztv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2nlteqkeh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2fzyszbkg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gt2dczsrrcj.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2ayvgzskf.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2pcoztbul.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2equnkxuc.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2bktrrjmp.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2rzawhise.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2aqjdxepo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmrzehtf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2qjigvxus.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2jyvxmtss.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2qjdpbfut.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2xenfuwya.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gt2vsgfsikm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gt2ahwsnqgr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gt2iwpecerq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2whiixunv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2xmcibzig.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gt2jwiqatpp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxieoeo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gt2cxnmcaix.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gt2witktxof.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gt2dcadduql.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gt2fsqzueax.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2eswrwcly.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvppais.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2uodoihoo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2hkzmmqse.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gt2aywfehqk.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gt2hlywjxae.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gt2fxpyzinv.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gt2xopaxkph.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2savlrpcf.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2velqduqu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhpjrfih.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2bcooxojx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2qqjgabyd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gt2ianytvjm.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2rdsaegwr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gt2cqyfmamd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gt2mhsqvisd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2mibvyyfv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zshhpxsp.html


<!-- 参考信息 -->