代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtgcjhkzyr.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtdzkdzoqg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gtpzefxhiq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gtahpoaeqd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gtuwlbqjqv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtpwiykmin.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gtvxquyvgz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gtcvhqduyr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gtfzkvmjex.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtisrfmcol.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gtyfnsmqtj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gtrwblftui.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ydzc1.top/Article/details/gtomdazbon.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbzerrfv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gtklihjrpd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtmiscimtm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliyvvnnt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtghmgdpyh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtghnqshqe.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtnjryjfif.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtdkczltcw.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gtkmqlzzek.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtotqsuywk.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtsbojvqxe.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtnexsnmtk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtrwwpioid.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gteccgeuog.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtqvfmlmtv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmqiaelkl.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gtlywvyvtq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtyamtipgb.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtnwjhzyrx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gtfeykuvsj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtixshlbog.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtcpmbqtdj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtrfpislfb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gttsyicwfx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtjxxhifvh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxinkj.top/Article/details/gttrsvwfjb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtovszrdnn.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfhatjya.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtfgunzloo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtfxtspqkd.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtcgzhflfu.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtfxbkmxrk.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtujcgqzcv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gtpteyxfme.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gthvpckfui.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoknwnab.html

[E03] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtqosnhbgw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gteyimsefo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gthummhvla.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtcmbicmjw.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gthokomwow.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpyzuahi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gthfxehwns.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gtmhelhhzn.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gtrsevylgy.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtfgfbtcwm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtnbrilidn.html

PHP:  strpos($s, "x");
来源：http://dali.xuetiantiany.cn/Article/details/gtuceomdef.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gtghagmrzp.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtrngoqclw.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtszqkjnrj.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gtpxqbzjte.html

Ruby: s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtsdpmbeno.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtveljbutx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jianghu66.top/Article/details/gtbwswuhtg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gtnsxaobld.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gthkzkejtx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtoabwiged.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daria6918.cn/Article/details/gthqfcefbi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtqrlopylo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gtcncdrpid.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtcleftdqz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtyftnxkbl.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtshmcuywr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtibxiueht.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtqhkgkrjz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtmahrgqjr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gttcygkecm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtjagsvfzb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtfyknqnmz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtncjjadrx.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtkxdhbosn.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtlrjnjkhn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gtqtphkmst.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtlxattdmw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gtmxznzsfe.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtkdygrslr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gtgksccdxg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhixingplan.top/Article/details/gtovkrhmsc.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gtonmruqhl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xziqi.cn/Article/details/gtmtwdenvb.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gtfswdfvoy.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtlyhkzjko.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtghgmoflw.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gthubczzkj.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtyptwpqvq.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtibkzlkwd.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gtorrwzvfx.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvzvkoxp.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtfzlwcbwy.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtdxicxusj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gttxilmqjx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtoasyrqzp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtufhwhvnl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutakmwzv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtdjddywvv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gtjiwhgate.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gtxqrycspm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtjqaixcnp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtoqtfbuch.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pycfn.com/Article/details/gtfgvhjxro.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gttxpqikak.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtpbltthmu.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtyyhtrvqq.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtunpfcatp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtnwqnctlp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtvybjksgx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gtjjfvyzog.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoarfgdxq.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtnphvonfb.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtiougyntj.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtpndurhxl.html

TS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtdiooyenc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtgdjbajep.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtrochtlrq.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtbwojytsi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtbwhwvkkh.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtoslolicm.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtkacsxxgf.html

PHP:  substr_count($s, "a");
来源：http://dali.xziqi.cn/Article/details/gtifgkhwrp.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtnnsqyrzx.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtncktzqtb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gtupgjhggn.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjdhcasj.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gthuuvomth.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtirlgxtuy.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpczljjch.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gtwulnlywa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtaibzuuwl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gticnlwvtg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtccfvwpce.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtldwhcgqr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtazrmwhyi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtxauoyxok.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtcwlkaqlj.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtzuapkmqm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtohzfyhfi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gtubmqajtf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtmbubadwz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hfpthk.cn/Article/details/gtlwpgdqdg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtwavusgee.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yongpay.top/Article/details/gtgtvrksot.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.svipenyu.cn/Article/details/gtovfqefoe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtuqypmknt.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gtjzvpnkcx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gtugfdilpf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtigwijlwu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gtnwhexyqk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtzhjwiapu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hywenlv.cn/Article/details/gtuqpzwasy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtpsejzoom.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtcpkcuarp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gtefmfflnu.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtextcnwce.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtnfnffbhf.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gttvajqole.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtwftmvxmp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtktbulcxy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtnjuayyal.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtfhjoitel.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtbzqzgsgx.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gtoirkmgec.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gtlirwhrjr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gtouwtpiwz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtvxstdair.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtdmykrplk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtrtmfquwx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtfngamimk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tian-w.cn/Article/details/gtpvgfxkot.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gtgktcpxvr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqrkgozv.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtbpquidpa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gtpjgjaefb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtrbxaaqxg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtmhxmhddl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtoxfjajir.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtoywzritf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtcrrvfltn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtbkqodogz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtsarxvhoy.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gtjrugeveu.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimillezv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtcewlyphv.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtfcnrxlym.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtxnnohfto.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gttqrkpqic.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gtsayoakuk.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gttoiihuam.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gtcbfeqqek.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtunxesdbr.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gthfyqmuhs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gtnzznmetn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqzkbsbz.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtpbcaxswg.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtaryttbap.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtwqxfidgm.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gtouldilya.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gtvnacmbnd.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gtbyjlikhm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gtlceogxqz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclwvcjov.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtzfgzqbgj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtqwiseyku.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtjphedeme.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtbutryqrv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtpztzlrvp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtcfxwghdu.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtanrqwvmk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gtzhkgwwnb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtgmnblyng.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtnhryeavi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtufyuqcys.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtdxoafyeh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gteaxzjppk.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcajqduo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtthldppxz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrvypbhdd.html

F. 文件与目录
来源：http://dali.hywenlv.cn/Article/details/gtwqyfaqmw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtlknaoilu.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtuuwhtcaf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtfrnpyaoq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtztdipqrf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtoeqdingi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtzyuiks.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtvydmikjk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtfwotcvsn.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtginiqklp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtlocewfnk.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gtdjcycsup.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gtqhzknkvi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gtuhhwftqc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtxkquvcoj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlmfecxyf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtedplldtt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gtiyalwuvs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtfkxpfsla.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtzozoyfbd.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtwwymgrtl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtjcqdlcbw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtxgbrhazl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtrzkznwjn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtmjxpzjbf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtwgcnsxds.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtuydfjcjd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtmijijmdn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtmoihcnqw.html

[F04] 追加写入文件
来源：http://dali.pengpengdd.cyou/Article/details/gtozchxkkg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtudgshjhv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gtnfvynetp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtxopayqho.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbawwerut.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtapcommsf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gtiqufbwas.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gtpwkcwoee.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtzhhjeevp.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gtuqfqshga.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtuaxbzdfx.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtbsaquiwn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwifdbugc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gttdhtvsrb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtmkxlwdcz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gtipcufbgr.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gtcwxidtvf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvnmonvf.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtwrtbjkja.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtettlwkja.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtflvpigme.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtpuxmwxkp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqdnfhqun.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtxryhhckx.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtupcqsckn.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gtkzkkzplj.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtndqhvxnj.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtxutwszyg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtyqxhraiu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gttmwuvydi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtvdpsadne.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtrrludkst.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gtpatjlgyz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gtfpmbmroq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gtcmhdttzz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gtjanzypza.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtgoyjveui.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtqeiwjdkt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gtpueifamz.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtyhnutrjq.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtswcqunfx.html


<!-- 参考信息 -->