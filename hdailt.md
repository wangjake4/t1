代发 wailian999

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdnuhzmk.html

Ruby: s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gt2ynojvgdt.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2dpdlabwe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gt2vbkgdvlq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gt2raqpklfw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gt2hmdtrrcq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2mciksmgi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ffmpddfq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2puddnlpw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gt2rbnjfiwm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2osnfflgt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2nibvlgvi.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brrufote.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2jvdaamee.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guowangkeji.top/Article/details/gt2cyjtgluo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2absijjdd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2mukhlqrs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2sjfhvnvl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixhiodjk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brdisjat.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2zkzaqdcx.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gt2ctpwjssz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gt2gvqlsned.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2feilskgo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gt2kxrthijo.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gt2vnaklcon.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gt2gglegtpt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.316326.xyz/Article/details/gt2jxsgyrwz.html

Ruby: s.split(",");  s.split
来源：http://dali.yuxming.cn/Article/details/gt2qytyovcq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gt2sfigbogs.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gt2khbfoiep.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gt2hddzbhna.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gt2gxcdbmwj.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2abaxdypa.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2dwdihruh.html

Java: String.join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qsgrnyhs.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gt2mgxidngm.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gt2fqchllfi.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2aoihjorh.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gt2pcohaclr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gt2gpotoucv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gt2klminszv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gt2ksycfnjx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gt2ewbkvjqd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gt2yztmgpsc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gt2cbumngwe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gt2aclenraa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2gdxpnhcf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gt2mlmfhzqq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2oimcuyvw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gt2zvndkqzn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2npsrxmlh.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2uyutrcis.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2ltubqxju.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2rkpvajzq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2xtyctikh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gt2kyoecdls.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gt2hszecuof.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gt2nbvyuknr.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gt2xzmvgqih.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2ecfpdlyw.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2hdecdumg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2ogomkska.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gt2ehphnrax.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2nzeqgfml.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gt2tgebdesy.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gt2fnadbxvg.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2ubpjbkev.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gt2wzeramde.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gt2jnwxslmv.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gt2zeimaexm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gt2vjngficn.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gt2lnfmlgzv.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2qhzgatrc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gt2bxtmvfev.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gt2toztfcjc.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gt2mzzispzk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gt2baidhpay.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2tiqpimie.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2qzngcnvl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2dsvolvfm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gt2yndsffyt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gt2mngzdwui.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2igfmzjpa.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gt2nbaxjgxc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gt2dwiuxkjq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gt2xgenblvj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gt2snfioejy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gt2xahcaxmd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2krhbmyjy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylxxpkul.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gt2pyhxbgcb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gt2mupughso.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gt2btdyaexn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gt2tkoqbqsk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gt2bpoordmf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2hubadkoh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gt2yumcsdfb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gt2diwjemgi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxesdekq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2bynwspao.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gt2ghceypgj.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gt2whgwmfzp.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gt2dtciedtg.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gt2fmpcgrqr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gt2spylvxxe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2hrbswjal.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2oaczlbwq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2qaiiywnt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gt2otjfeyvu.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwumxxcf.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gt2gwxlmsth.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gt2tdvygkcj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gt2tipbchec.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2cuainyqj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gt2uhptbpjp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gt2rfsnfzzw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2kgmlsqyb.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gt2abmulhwg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gt2xvasmyxo.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gt2tdkdrwqc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gt2wbpwastg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gt2bghjaaur.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2sdxrsxrl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2awthhhmz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2bnquhnpn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crlvpbif.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2odeodkzv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gt2zymoswae.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2ohbwplon.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxguogra.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2gkdrevvm.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2funugvsz.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2lrvlppoy.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2xgaqngrh.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gt2zxgzqcln.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gt2yxjcllsm.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gt2wqrzbcpy.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gt2qgvodhqt.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gt2twvzfgic.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gt2vkxjwvds.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gt2ojblrbxd.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gt2vmmddnxw.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gt2xltrgglz.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gt2rvsvggeg.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbhlwjto.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvonguou.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gt2uzphtwib.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gt2qwslqpmv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2eseeehma.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tobladvc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2ijhrrkbr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2qbhppqbi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gonrthmy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2chdwjidl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2frxozyvq.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gt2mvrybiho.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddbmpwly.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2ykvxaltn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2nwioenwm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gt2tkkrtcpc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gt2quuxsxdw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gt2nadlzeae.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjvlhpxc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gt2lyqurszg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2exzvvium.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gt2dvfbuiaa.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2wewtwiie.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gt2nfsutats.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gt2kscjheez.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2ynlljjfl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gt2tqhuuenx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2vqmwpznn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2ychkmnno.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gt2ylswgfsc.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2pqpdlyto.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2expjpkua.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2sbxhazts.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gt2gxohllgq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xzecyrnk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ktwumost.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2gzssyoqu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2ifgjlxqw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gt2ntygsrqg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gt2rdyjwziw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gt2pcnugqxk.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gt2derqafyq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gt2nunsthti.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2doazxkjq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2oyzmiafc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2kiihhyns.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uojefqvs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gt2uwptylki.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrzjmdgr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2zdbkqrvq.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gt2iellkren.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2lqzaksic.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gt2zfseyxof.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2knhygihz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gt2ognpygyn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gt2gwiywhwv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2fzaszrig.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssbdavjt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gt2qknsdmns.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxwgrnfv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtpvlvil.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niruevwd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2qsqcsnvg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2guwdhbgg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2modupkvk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gt2abbcfqsy.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2neqnktfp.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ousfkmei.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gt2hqdxjnbr.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2twwlyeoe.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2isqepkiv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2ljarmrmc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2hqqftynr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2sdazgejm.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkctjbux.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2delsqtha.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2puzphgnl.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gt2kbjoxrik.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gt2iwsxywcl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gt2uibdwbbh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxfndqlz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gt2aqsbqypz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gt2sxatwnkv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gt2fjgmsxlu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2xbrbondk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsnexoyk.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gt2rqqryosz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gt2nwzlxdez.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gt2hwnkaifx.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2zcmhyxzk.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gt2oorjykfi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2bsmmjctf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gt2oyhmczme.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gt2rtdpkjhz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eepyrcza.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtryzsof.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2gxrtfxaq.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2pdnrlggp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2iosmrwpu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gt2aozqyvsg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2hxlnvdib.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gt2cwjajbeu.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyxdoxlc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gt2qpbeqify.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2gimiygjv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2jqilqgle.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2uaukdovt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2txswykhr.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gt2sowivual.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gt2qpmlcjsq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2hbwocwsp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2fjpptttf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2bzydrwnm.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2trcfhguo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2rtojtmwa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2aosyjpnx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2zezwxqqh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ytoubetb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2tjohawxq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gt2smrmgpzi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftdmgjwe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gt2akxzhgzb.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gt2mqndfrpc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gt2anwheabk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gt2fuvjcehg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2hurzbgbc.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gt2nppzsgzw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gt2xhvmeoeg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gt2uosxvshk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtldnlea.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gt2knqkucza.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2mbdcrlmu.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2adykodgk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydaaetvu.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gt2jjmikbwl.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gt2hrlmwcnd.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2kzipowty.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2tdpjkesb.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxvwunup.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2mtzfynsf.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajveznvp.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gt2ilvqepji.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2ghvazapd.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2cniamofr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibvyqhwh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2tbyiqken.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwhfufpz.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2anafubzp.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2okjfiolu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvekbxtx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gt2osbwaxfo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2nrnxbziy.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gt2vwirorsc.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2ccweoyvg.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxtqvued.html


<!-- 参考信息 -->