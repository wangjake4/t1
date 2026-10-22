代发 wailian999

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gt2rigmtgle.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gt2xakndnsj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2ifhmzcrq.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2ntzuyebs.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2avthzuze.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2fqzseqsj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gt2lyxmpayg.html

Ruby: "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gt2abvjhanv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cqqwz.cn/Article/details/gt2hndxsipx.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gt2cjuoqnpw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gt2jlyeamkt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2sfflnyxz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2hupvlzzm.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2hwuucxvq.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2wpbhkhsw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gt2rlsiznoi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gt2nwbxbhjo.html

C#:   s.Substring(1, 3)
来源：http://dali.ybcxt.top/Article/details/gt2ckztqbct.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gt2lbzcnypw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2novlghvb.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjmusexj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gt2kqxwpcvn.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2xdspyssc.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2soapdhhl.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gt2sxvwljwc.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2oyujkegt.html

C#:   s.IndexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2xrdlzncq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gt2iycineza.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2fepouhiu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gt2msdkfskg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2sldewjub.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gt2tsiriken.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2abubicwb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gt2kxrnpoix.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gt2zftkpttv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2ycjxfrgq.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gt2wllouwpp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2wftgrbtm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.iojbl.cn/Article/details/gt2pjqmunep.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2ylxxwmqm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2ddxlxbpf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2pleplbaf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gt2sgfsomvg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2pfyxyblo.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2ekvtzafh.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gt2tojuskfj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jlsjyb.cn/Article/details/gt2tshqlklc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2soozgfxh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gt2hjcklfju.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gt2bpzrngkp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gt2ogyvjncw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gt2ncllkrly.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gt2umltucwp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gt2nzsihuqc.html

[E08] 数组按分隔符合并
来源：http://dali.9152youxi.cn/Article/details/gt2vjemvfeu.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gt2vlrlfmgm.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gt2aicrdkte.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2tretfjyj.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2ayuayleu.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gt2buepshbw.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gt2ciukkvlm.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2wyiwzjmg.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gt2peuzlcmt.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gt2kouuipji.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gt2lmmtvlll.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gt2jmnetxqz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2nlxvrgup.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gt2uvoonxlw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhxvife.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tumolhcb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gt2lsfdazkn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2uxprnyux.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gt2uwqivluw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2yutuskji.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gt2lfpwnhii.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2lgbyiiue.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxffwvaw.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2ptveoixr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2pmwuikfl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2jjmevhms.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymujhlme.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdncclru.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2nmecjxie.html

PHP:  strrev($s);
来源：http://dali.yuxming.cn/Article/details/gt2dfaslgqb.html

JS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2hspzmzeq.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2umyjunkw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2srhlqymt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbbdqisk.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2rekdwtjh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2jewkqvyj.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gt2aknczkgv.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gt2nqpozmty.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gt2saimrmsp.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2bwfjlkmp.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2zxardyca.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gt2rgwstthj.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gt2iemcummi.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gt2gwhpcula.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gt2haewkrhm.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gt2eklvffda.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gt2agxmwngk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqpffxtr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctzhxfaa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2orffzxgt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rzanbjsg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gt2vosbyxgo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmsjdxce.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2defuplil.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2crnmozrm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2reakzhar.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2nzovhfpl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gt2mjqbudzy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gt2eenljhcf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2kljjjjxl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gt2osioghur.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gt2ivbxncoo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sawgkyyu.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gt2dprkmkvc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gt2paigehik.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epwtgrok.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gt2bmazhxgp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gt2rijlyrbs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gt2rjjwnwua.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnacrpsx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gt2lxkjeieh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2pgydkmcp.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gt2vejefqqb.html

Py:   f"{1234567:,}"
来源：http://dali.aibaodan.cn/Article/details/gt2wakyiyps.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gt2ugnsfmeu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gt2pmkdrxyi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gt2ffghzjid.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gt2wwihzjkt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gt2esaxphxq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258888.top/Article/details/gt2olefktah.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gt2tzzmcftz.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gt2cysmjhsg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gt2ujtkaejm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gt2cspfcgtp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gt2ahtkrmdd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2czitkgwb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gt2ppbpmlrs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqvmrvyk.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gt2fmpvremn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gt2qgjuroif.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gt2zuvfrbhj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gt2fotuoqez.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gt2bdioxbmq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwtdgfrx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydviublm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2gofgcisd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2dskyooxt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gt2wndesqbr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gt2opkoawbj.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2havkuhpj.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gt2ogalnecw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2kxogypuv.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2jnwddmbj.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2pmuiwxzg.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gt2khnspzey.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gt2iwxlouew.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gt2tchsoprf.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gt2hakrqzea.html

[E20] 判断字符串是否为空
来源：http://dali.9152youxi.cn/Article/details/gt2dczbviig.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnhtqoed.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gt2llprypve.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gt2rhyvrxde.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gt2yglvsmyq.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2pmabxegh.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gt2xzsnhahq.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gt2eduzuqhs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ieluzwfx.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gt2sodxkyrj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gt2ntwqgcjs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2zmcrfdwv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2sezmnbjk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2rsmiauxt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2ozrixixn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gt2ujnklcdc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2mpgxkdrh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2hxdxvshu.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gt2rkystxnh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2vhximwdm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2azsmhtcx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2eknnefqz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivitrrxg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gt2zhyasiha.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gt2phnjggnc.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2zuhbfove.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2hiixfvbw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2veukjimu.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gt2qrcizzvn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fitanjby.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gt2jzsmcnvp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gt2rmolmgmz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snllrour.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gt2dfcnhqpv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2tumnucdb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2mbliksch.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynbcdoqm.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2iboadpfa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2lupnrdsl.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gt2ijckxiph.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gt2xghttipq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xylfe.cn/Article/details/gt2qojvbnaz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2zgfpejst.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gt2hkrtgrpo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2hgxwxpyr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gt2sdmedufu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdfgqlko.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gt2nyedufcu.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gt2widbcrfv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gt2mxebdsab.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2imnelifd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2lcmuleil.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2kgkxanyg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2dsweizhy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gt2wulecsif.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2wbsiuidy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2gnsaneyr.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gt2iqkrilbc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2shsddxui.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtlqgtrs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2soanhhyt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2yeiotarn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gt2xmjwjhnu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2umiarmuj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gt2puscrjgd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gt2gqjftriu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2kmpctkzo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gt2jmqikkpd.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2duylqbnj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2dfnqglzu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2kmvsabuz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcfgtnfe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gt2ndngncux.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2igdtybrv.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2wrfwuped.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gt2nvmrwdfs.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nevliedm.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2xakvamkc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2pmguaovd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2cfhzbqoc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2pwyzlvhk.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2erallzsg.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2rngpcrmz.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2qlnbrirv.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gt2vagvuoss.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gt2sheewbmv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gt2cncfuino.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2xgqsrvco.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2tkaejnsn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gt2urzkpgek.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnkcaepy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gt2qzpnerjl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gt2bidfkuxd.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gt2kgzgiztp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gt2rtosweho.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ltbckkqc.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrqbzqek.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2fqkvegma.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2jdwieddc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gt2nxkhuxos.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utuaenja.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gt2iutbyjwz.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gt2ohvqifjf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2dbmuvlzk.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2oobjqowv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2pzasexxb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gt2nduzlyqy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2usbjulug.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gt2uxysfggb.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2nzllczuj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gt2tyjoikbq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzvphuum.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2rbcnotwc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2ulqozbjf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2nbadfvwy.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2bvmuaync.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gt2oksejynh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2hzkdytzf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2yxspirwk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2osqnurxi.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gt2cbfsgirn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2asyblgpo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2cijduprx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2qtbnhqwr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2txegedvd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gt2wohltban.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2errtmihm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2ckhiakgh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gt2qjzplpsf.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gt2aalnvkaz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gt2bogelanh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gt2lffvhhau.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gt2ikiwjvga.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gt2gmapanvm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dmixjrgc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gt2aqdybele.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2uafonruo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gt2hzfaartz.html


<!-- 参考信息 -->