代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gtcbdftvag.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gtxhwbqzyw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtuwulxqrx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gtecrzhnjj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gtxehjvpol.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtrkomnsng.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gtyoiohgwl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zdqjudy.top/Article/details/gtubuyrxkv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gtuyglryka.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtkoyprdwz.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gtogliarii.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gthzyjcdck.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gtvupnsflp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gtnpaujsqv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gtmqebtxng.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtcqwwiyuz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.feifeiyinyue.top/Article/details/gtaosnjgxu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gthyspncoy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtstxibujr.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtdviwlxgm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xziqi.cn/Article/details/gtrnssobdy.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtxgxspwiw.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtmxjwabve.html

TS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtmpseqhco.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtjzrohser.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gteffhimat.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtoiroytpr.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtwkrtkmfk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdpgxqarc.html

E. 字符串处理
来源：http://dali.cdnleiting.top/Article/details/gtwekqtqkx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtruomzsct.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtvkzpdlga.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gtxflzewht.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gtscwkcqvu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutymcfno.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtromerqlu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gtabzpqceg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gtxcjovpaf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gtmyzncuno.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtkdnylqob.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gtpsyhhkex.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtbfptjqad.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtwugalolf.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtoxaoaret.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtbzrwmfkm.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtdatimefy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtqjxidebt.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtooefszqo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtpjfzyuin.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtjirimfrb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangdashe.top/Article/details/gtttmlltft.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtblfwzcsu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtlejgmwbq.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtsazdulsv.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtbckmozro.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtjngjapfa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gtcmjcxvxb.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gtbsnmzpov.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gtwshcjhvp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gtukczerpw.html

PHP:  strpos($s, "x");
来源：http://dali.zdqjudy.top/Article/details/gtrojltmde.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtppdjpdkp.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gthvmtoasb.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtdivlivhm.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gtvsivpvkd.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtakabghwr.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtccqaourg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtueqwijrt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtnbevmwyq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gaohongyu789.top/Article/details/gtwdgggwzq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtsyacmidt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gtnxrknnef.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtgtwvziko.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gtihtjfbzl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtkvzloigd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvyqtdtz.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gtnipzmlvs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtjbavlnlj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtikisblnb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtngigoldv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtgeejster.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtwwwehjws.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtxmovions.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidsnxyor.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtmtyknqhj.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gtorkwaddp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gtwziladvz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzzvqyzv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtqfdqaeiz.html

TS:   s.split(",")
来源：http://dali.yueranfly.top/Article/details/gtphreofzd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtqlemzfhz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gtvfzkhjnx.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gtpebcurgs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gtqtuwtbrz.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gtuvfssmdy.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtpfapfelu.html

PHP:  implode(",", $items);
来源：http://dali.nanxinkj.top/Article/details/gtzsewccfa.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtjnycyhdu.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtxlhtmbtj.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtsxluudqw.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gthmonpmcn.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtfwesacjw.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtsceuhhzh.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gtygxmfgwv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtdmpccpux.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtfjdiguax.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtzcvwpjvz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gttjuizfjb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtsdtewund.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gtwwpouyrr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gtemsjovfk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilltuchk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtfvpqxbvm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gtltyhsdiw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtxabeacbb.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtaizyztzb.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtkobxdatc.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gthxufpyjl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtkbknuauw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtgjshstdp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gtjrgvqhgp.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttevhbkel.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtbgyymowl.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gtambzdcho.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtfxvzkqbl.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtahisvapx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gthbqkcmhe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtzwmiplfl.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtymmdazzs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtyhnclliu.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtpteolwvt.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtxewrjdui.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtrjpqotry.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtpmmdptgk.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtzqwemdzh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtexuqrhgi.html

Go:   strings.Count(s, "a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadmiujri.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtnouptfdp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gtadmdxfpo.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtztwclaoh.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gtuqvmzxzx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gtpfwggkqj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtpmndawhs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtowhkotzw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtuofjxxkj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtksrxiwav.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gtlwxtexaf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtzunlfdyw.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtouyviyxk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtapmtnivo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtltbihhjo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtajfchptp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gtywcxyogx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtlhmwgvnw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgpsvjsp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtqdzqbfyl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtwjkcyjic.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258888.top/Article/details/gtjbkmendp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqlfannm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gtcefwbvrw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtiambdsoq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtdcgtkuud.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gtgwwvdtap.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gtuqyhwrzm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gtreahyoks.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gtoagnpovs.html

[E16] 数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtezkodjkz.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtrmljlwob.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gthyutzheh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtfkethlun.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktokthle.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gthptfkthx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gtpivzjwlh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtiylogufa.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gtealgpngq.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwzrtnrs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gtlvnlfhbu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gtcysgbucy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtvaiuscby.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtphwcuykn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtxyjoaato.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gtnksdmudh.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gtnqcazvzw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gtnlwqzaow.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gtewlotxyg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtyzhlzmba.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gtkskhlpwx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtitpmuuuf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtywhsjayh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtuqisjqqk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtpoinibmg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtmlidldyl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gtznhghlmu.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gtpdvwqjaw.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gtbrnzywiq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gtvgaywbza.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gthjtjscgo.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiepoelzf.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gtwlpxiiiw.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gtnlugbyde.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtrgfctgkb.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gtkojcniek.html

[E20] 判断字符串是否为空
来源：http://dali.shuidangran.top/Article/details/gtplzmkheo.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gthckukioh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtwwzyrkdo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqvcooylo.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gtgnhluuus.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtuaixbxst.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gtqfcfvudl.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gtavkewogs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtldzkmbfw.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gtienfhrjz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtezgjfyva.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtuotgebpm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtlrgkxwlb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqodkszu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtwfqcdqry.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gtxlmcbhvz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtsocjckuo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtzlstrhor.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtijxewxto.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gtowwfpxbc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gthxiljzmv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gteqgyagxz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtjdxghcpp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtikckmqvk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtgtxxqgtk.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtqaazmujs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtwrxdohkc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtklcphvhz.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtpjqulcnv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqohoowdf.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtfiuxtxyx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gtlkgelzel.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gttzxsvwfj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gtzuxjcghw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gttqmuigsa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtynrnhffa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtdthtjrcd.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsappgeku.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtgvnwgafq.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtscxecelt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gtfuuxllks.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dianchejie.cn/Article/details/gtmgfzmmcv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxecdgyjz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtwjqkrijr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtlmtkyare.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gtuvwwrsqv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtqlgmobei.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gtsmpdupbu.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtlwdrsxae.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtbilvnaan.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtdpgcwmmn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtchbihodi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtmtsyhcpz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gtavrnuoow.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtttpofnmq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gtgudurotr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gteryqmsfb.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gtumnihmet.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtpcjjxdlo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtdgtiyyxe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtuybiwtjq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtkyaccwml.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtrqlicomb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtveiorqer.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gtkdoteeal.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtokritube.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtfeyiymeh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gtkpghidvj.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtxyoxemdl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnwvmgjqe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtnjzytqgs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtrnhhxkav.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cheryme.top/Article/details/gtkcnuoerx.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtvcixjhiq.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtavvhhupc.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtzhffpqfo.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnabhcbwc.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtrvupjwvt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtsiaoqxse.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtofsvcape.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtvcghsbyd.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtcsyrjqss.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gtjzlpetyx.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gttemlzned.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gtdhwjedze.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtnfgeptfb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtthbdcvii.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtpvpzwcof.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtopbjpnjx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gtbwrlyrks.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtrraacwmx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflcncgqf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gtoejrxztq.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gtokkjzbhj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtyujppfic.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gteluckdlo.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtypfszjkv.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtxnqfbvrj.html


<!-- 参考信息 -->