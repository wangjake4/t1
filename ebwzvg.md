代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2lvmoimmj.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2avkxmnof.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmybywpd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbgnszle.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2wirwlzcv.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhcxoyxu.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gt2gjsllldt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gt2fmegizkm.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gt2ejeuxmqy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gt2oycwnkhk.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2kqahuoga.html

Java: s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2yyqokqfp.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gt2rtyfjmky.html

Ruby: s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2zudatxcu.html

C#:   s.IndexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2gpqsgdgw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gt2bzqicgcp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gt2tltpfdrz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.svipenyu.cn/Article/details/gt2qcsgidtc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2yfznvgpd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gt2ueriqugo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2gnxmsvtt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gt2bewbvuml.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2szilzdrh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2visnonqg.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gt2zxjhqwlw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2tqfogkiu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gt2jsbmfvmu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2opirltka.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2lhbnklri.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2zzzxlbnh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2sdkrjnqn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2skzrwsrt.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2orvcuolk.html

[E07] 按分隔符拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynzgxhkf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenlongwang.top/Article/details/gt2ofnidsfu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2banvczzz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ppjwa.cn/Article/details/gt2wcjcuwzb.html

TS:   s.split(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgiifstq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gt2tjcwfrrc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gt2zvwwyaex.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gt2fzdpnngq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gt2gpbdqkow.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvhakvqf.html

Py:   ",".join(items)
来源：http://dali.daxiang520.top/Article/details/gt2piyfesft.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gt2dhzqdpmj.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gt2saywjpyf.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2bokzbhmg.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gt2vzdqrerb.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gt2bpwkbqqh.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2kgtkljbw.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2zwziwvjk.html

[E09] 去除所有空白字符
来源：http://dali.zdqjudy.top/Article/details/gt2ozirypyv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gt2zfkomtyq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2ppfuzewh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2vqbrqxkk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gt2lkmtkxbf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gt2ecrhavqj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gt2jcqbquuq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gt2nhpfxnza.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2pxtqdnzo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gt2pyltteny.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2lwwetrtq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gt2fgwdhftk.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2wzzdftdx.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2oggsqjov.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fefyjppa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2fokhjtvy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2furelvxi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gt2dqrnrkev.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2wdirzlmg.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gt2pvqpsafe.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gt2tiyktfmx.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2zbpekzvy.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2wtfistid.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2anqpdffs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2rlbaefvi.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2prkrprnm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2wunxqcsu.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2rifnrhos.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2prihbfle.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gt2hlkicsoa.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhcwbgch.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2klbyzjwq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gt2hjsnfucp.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gt2gvvpwiuq.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gt2fietockj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjvqmbox.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2iidwdler.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrvdifaf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gt2sojzhurh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2tgspihpd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2zsqsatrq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2zhbtkiso.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gt2ljhtjgia.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gt2yanddjlv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2qbagfgjb.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gt2tenbszxl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gt2kguqjpba.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2inqiccaz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gt2rykpzdxc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gt2lqgauada.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2bkremnzt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gt2maiyjkuj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gt2zvejhegr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmhjzfnv.html

[E15] HTML 转义 / 反转义
来源：http://dali.dashuyun.cn/Article/details/gt2bykwsfyt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2nsqoxdvf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gt2lirawmrq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gt2tmbxcoak.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbqrpujv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gt2aiulzigv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hopsahqo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gt2utagliif.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gt2vuxbnhkh.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gt2dtjccgnn.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gt2kgquhjsa.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gt2bkojabhi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gt2dcgptbrq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gt2ggwejicq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2cbzoyejg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gt2qdmemiwy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2eexbhmmy.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixyuuonf.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gt2bzrgjlno.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gt2cpadlsub.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gt2sdpcygbp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gt2junteqxj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gt2zqsascdu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzjctfas.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gt2uhkkyppt.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gt2ogoqhtia.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gt2whoicykp.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gt2yydgjojs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gt2zbwurafn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gt2wxsbghvv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2bkksikhi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2tjjrndfa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2palpzlzw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2kqvlywhe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gt2jdqlnpma.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gt2uhglvznl.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gt2tkydbkvt.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gt2ylozmcyw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2gehrjuga.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gt2ssuhtcmu.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gt2zoknnqjk.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gt2ltpumkjd.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gt2aotdyshl.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gt2lknunmni.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gt2xitsznde.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsteuxpl.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gt2whgnxdex.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmmkgvrm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gt2tvbzlqaw.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gt2pzmhougp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gt2hceeahes.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gt2irndqmme.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gt2xavrnpoi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chwrswha.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gt2flgcrhwl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gt2dzmtfhmv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2drliglbl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2pjbipboh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2wqzplfkw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2lrmtoney.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gt2weogeugt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2mhwrhdev.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2vedvsjnb.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gt2aujmrkld.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2zgvqoywd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2ltfconjs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2lfxacojh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2cwzncsto.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwxcowia.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gt2uiibfmas.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2wvknjaux.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gt2tbbybjbz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fopdsksf.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gt2kfambrey.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qdvzlsoe.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gt2iyapdahc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gt2zbogdhrd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2rjyhxwwb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jlsjyb.cn/Article/details/gt2zxkywxtg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoksclq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2sbgjevhu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gt2oypxjygj.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2dzolrwbb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2litvggzf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfwrewa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gt2reojordj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gt2sfezdmmf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2siirpjor.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gt2fmhgfidf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2gznrcxtv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gt2rklvwlid.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gt2ymfozrwi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtxxqymk.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gt2bgfebhdz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gt2wmapgbuw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2ocgesqll.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2pckxfrvl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2ytldvxvc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2ersxtoib.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gt2czpffywq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2xsjcrdps.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfkkfcgw.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gt2jardygal.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2joeofbig.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gt2xojvihdx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2vpdocpli.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2rzezbrxf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gt2xgjorowp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qifpmilu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gt2cngxpfja.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gt2bnpxsvzo.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gt2akrwoelt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gt2kavwfswp.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2puuefeca.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2mlprdsgr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2zkscrten.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2lnywitny.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gt2cbgffkil.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2cduqppdo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2gucyravs.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gt2qezxpbdx.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2wkwcqfsb.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2nyzwgvmk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ogygxajw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2mbznxvbo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2xgugnhwh.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2daticykw.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2kgefyzxa.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxthontu.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsupiwsr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qchdrhex.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2spqszasz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gt2rnptjdlo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gt2eylxknff.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvetgqsp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gt2tmvfvfth.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2hsstdtjw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gt2cfqiicxv.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gt2cwxjekga.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gt2ekxmhhzr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gt2utwkbhiz.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2swvlzqzm.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2ncrzajxe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2ctsksrzd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqdbaojm.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gt2wehhihen.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gt2sqgwvaqy.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gt2vttyhgpl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2irjajomc.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2ftefuske.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gt2cvhmahti.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gt2vilqijtp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2fjviuaep.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gt2uwmyxlnh.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2omyvrqns.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gt2mgkrdjro.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvyuoqlq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbommaci.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2cppadtea.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2zyntihlq.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ykzgicvf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gt2qoiiuokq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2jbgtcckx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2hkvzueld.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2rcjrdezi.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gt2xzcsfvur.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2zzcsfqmd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppoxmnoh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2soywqjtb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2wljlfwkt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2raurzafs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gt2qbujwpwi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2nxwbmvee.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpmewiqh.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gt2nwdzpktr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gt2pgmvpjeh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gt2ufesbfmg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gt2nwkkmyfy.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2yspxwbpy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gt2mvkwjxbw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gt2xfqwyfko.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzyaxkxo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gt2ismbnvdm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2zgrlwtsc.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gt2jnkfcztk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lhtoymba.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gt2iyntktfu.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gt2tsljawnh.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gt2ferryhal.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gt2eqhxqtru.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gt2aapcfzfo.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2bnnhjssc.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gt2yujwqigd.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gt2xqviauur.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gt2upvqvpho.html


<!-- 参考信息 -->