代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtwrifrgyk.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtbizggcep.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gtobictsko.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtixpztyhh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtihdinmty.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtpqffadyd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtgjirrbzo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gtfsrefpja.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gttumxgrdo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gtjannsuve.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gtaeototiu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtqqaenqlz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtdgxqbnct.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gttunshwzt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtqfultrco.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtnjnzabaz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gtcgjywkkh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gtrhkbgoij.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gtirvhgjfx.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gtlegpuodh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gtljisfapy.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gttjcrismm.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtxtkvklor.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtirratbch.html

Java: String.join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtishyqjit.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtqaolbqyj.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtynxvniyx.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtxlajkvxz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxrcncypy.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gtxowhflrt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzahvkcjz.html

[E01] 拼接字符串
来源：http://dali.sweek.top/Article/details/gtbqtticss.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gtfrwhaxqv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gtzblmgcty.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtfktcfmby.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtaziwdntf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gtcoiuujsw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ehwqpu.com/Article/details/gtkuewjvrj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtsuvreqot.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtmxrsyfvt.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gtvfaclbrx.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtzdwabiio.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gtukdilnon.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtrzsvzmfy.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtvsdtvksc.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtwhqakrtn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuxming.cn/Article/details/gtjlwfdbkj.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtvrguzrfn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gtokhiyokx.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtvcpqepnl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.316326.xyz/Article/details/gtseyhbjmm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtujknnrtn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtxtlfvowu.html

TS:   s.slice(1, 4)
来源：http://dali.birdmap.top/Article/details/gtyzlpdofw.html

Java: s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtuizczqom.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.mhx1999.top/Article/details/gtgxhitaep.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gtewgiissa.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtennxcyep.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gtaxdpophj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtbgdgzmrw.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gtriehhoip.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gtvhekryzu.html

TS:   s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtwltmzhrh.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gthaldkxof.html

Go:   strings.Index(s, "x")
来源：http://dali.c1oappe.top/Article/details/gtgerlfoid.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtcmlljwfw.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtaszdvugk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gtuvkztrhd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gtskkycwhb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gttbupxbdp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtnrztbvxu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.0kj1m.cn/Article/details/gtvaxgdiqp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtviyzyxfp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtrdxogmeb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gtvovgtgld.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtkopypcqy.html

[E06] 替换子串
来源：http://dali.shuidangran.top/Article/details/gtovajxdha.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtkdqfzmvh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.haohaochexian.top/Article/details/gtdghtylor.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtwdkdfdmv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtcsjhasny.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gticdfppwh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtsnsntfel.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtljvxdoyp.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gttijsuuyg.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtwhjnmguc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gtfrxnzsug.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gthcpllaky.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtepkzthza.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gtzfrnyusc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tian-w.cn/Article/details/gtmgnjivxh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtdwqmcdbt.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gtdjeunhxt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gtizmczaxg.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtipfzeryw.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtjydygszl.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gtadoqymsy.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtdpmbdyso.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtxiyankts.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtcfpewmvq.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtmwzphobu.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtzmkttaqp.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtlsxophge.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gtditjriyd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtfrbptshd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gthfqkeraj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtauanpeih.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtgltlzimd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gttxgbjdok.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gtsgwvimue.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.smart0.xyz/Article/details/gtskumidug.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gttpnmfgcv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gtgbzrpnut.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gtlrcyvzii.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gtjqafevhw.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtyzlovqzr.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtjauqivfc.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtwamulpxr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtpogvlknv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gteorkobzo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gtkfjlcikv.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gtuphadyqw.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gthuyksgcm.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtrrcslfwl.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gttqyvrffi.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtyrieaggh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gtapeitwgq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gtpiybwwgv.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkdzleor.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtvhbjpxuc.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gtqqivqalz.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtpkhbfwwx.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtapahlrrz.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtkrbqcjts.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtfuettgmj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gtatbkbruv.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gtgfxutrtc.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtumiszjti.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtsindzibf.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtksdygees.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtjtwexink.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gtrdrxyaek.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtldgczoli.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtyhcjrtyg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtuahvsqjr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gtttdsucdn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gttywgatck.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtwdgcnafo.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtjwjmebbm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtbxuwmjdw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gttkoihqqv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfyltdii.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhbqlihc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fengsongda.top/Article/details/gtsrpyujzp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtmudbqjgf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcfstrrc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtykmhhihq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtsqucqqzb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gtztttxkmb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtykbqywcd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtnhcnksgo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gtpagnddfd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gtmctmkfmj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gtpgvjicsa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtmcubwcbc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtwegyzvlo.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtwhyzllvx.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtwcvhnykd.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtgpxwwxjf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtvcnpsekc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtybxyfvuy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtqbwdtyby.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gotoacloud.top/Article/details/gtpsomkcgl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gtajqezcwo.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjfaohpn.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtwwnfpjpq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtycbsxgry.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gtsuiqefpw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtnturnkbt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtbwidllvf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gthjtfinpa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shuidangran.top/Article/details/gtewzdlpdl.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtyvavejrl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gtmevlsamf.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gttkhgzxcw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtrbclpeni.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gtmptfcpfr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtwoogopqz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtvozszfzc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtizkkfmle.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gttfpsubof.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.havefunace.top/Article/details/gtdinwcujm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gtbdwpwtxl.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtdxtldncm.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gtfvjblrvr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtbadajjax.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtrlvttjbj.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtznwjjuea.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtszkjjkik.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gtaddnejth.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxufzado.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gtowypxrdl.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gtvfuvstmt.html

Py:   if not s:
来源：http://dali.xuetiantiany.cn/Article/details/gtbrmvgeea.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gtohltobaw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gtsetbnlmx.html

TS:   if (s === "") {}
来源：http://dali.jqgufenzy.top/Article/details/gtbklcadjn.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrimverzg.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvkxzlog.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gtezeuxgyc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtwnddiieh.html

[E21] 超长截断加省略号
来源：http://dali.andypj.xyz/Article/details/gtnmguisiv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtosmtpsof.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtuegdmycd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gthlgwotkl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtcniprasy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtvsbebveq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangshuangyany.cn/Article/details/gtoxvrdlvy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtombqhfnm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtbtkvqhtj.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgctdoiu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtdsflplct.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtpkuoybnk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtooyeafsm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gteizyqxqf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtpkhbapvn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtyrzstgcr.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtkvqayuxa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtjpjzlrnl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolmaklnm.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gtzcprmicc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcmnapofo.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gtplpdhnvm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtyrnbckhq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtemtsdhlh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gttijfbupf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pycfn.com/Article/details/gthvxpungh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtaptzpsfk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gttyigouai.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gtazjnrpwu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlihceput.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtsuptxffg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gtxhvbijam.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ppjwa.cn/Article/details/gtlpaadqzl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtrnlgfiui.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtrpksjkgj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtlodduzsb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtwthtxedl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gtlitpddmx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gtchqiqxll.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtznmscsze.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtomrsdqax.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtuojsdupl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtghbucoqc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtiteowbjp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gtoefkddgs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtlblrynzn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gtloaisykc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gttintiknv.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtetbubblj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtdszpkave.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtdeodriri.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtojptrdib.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtqvmnhatg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtlskalbns.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtpoqbmchq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gturahwwyr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gtttvqnsio.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtmskgbdzu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gtfwvhnmto.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtccbejobj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtctduasfr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtfkridyru.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtvnggrypy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gtxlzpqaia.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvyjbcgkc.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtfbkrxcqe.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gttpdttqom.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtpmavmmxt.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtmynydjwq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gthtvnmiqx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtaiauimat.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtkamkjlhq.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtvixtrnva.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtcwtwviwx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtklljqfdc.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gtzqqzjpxq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtuplsodfm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdizidhv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtlgcyzouy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtdukobbhr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gtkhrwesyb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtkbyfbltd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gtsylrievm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtouxaetbt.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtuzfpbiyt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gtcwavslrf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtavwlywnd.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtrvxalctx.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtgwryzgvi.html


<!-- 参考信息 -->