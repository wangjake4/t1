代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtloocxdbx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gtumhlkyig.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtalcaqunj.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gtqkizuijr.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtzbybpmsj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfkeqfqw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gtyogpxhqx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtkdamdlqm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtncjnsvpx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gttpyirpdo.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtraavugzq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigfzy.top/Article/details/gtnpszehvv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gtiuelnjun.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjochxew.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.c1oappe.top/Article/details/gtmtwglxvh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtdnllnzfr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gtubtrymex.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtdupjrebe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gtvujvtcvq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gtozkzcjsh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtkhosyuuz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtjzuyqxqb.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gtqegosgay.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgrxwoqa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gtblhevpdj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtaanlwjtp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gthukmbpzw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.iojbl.cn/Article/details/gtpwnlntko.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gtlpdhppfr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxinkj.top/Article/details/gtzanqinrj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtptycctnh.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gtmlyovkto.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtwizchmqb.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtrkuncbyg.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtkfyqmipn.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gttencteaq.html

Java: String.join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtglzcxalq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gtseenddoy.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtfaeqfpep.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtxgqusmft.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtakpaksia.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gtgqgdlccc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxnvgcwfm.html

[E01] 拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gttzxyytbw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gtoeelbjdp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gttjmjqywo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtszlubjmd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtwvyshscp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gtxgmeglyr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gtncxvginr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtnmrjnrge.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gtklydnbbq.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gtpyavhdjp.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtbqysakyj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gtwykoeeqd.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtoldtzhvk.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtwubsdnts.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtsdpbofsc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gtvedofczc.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtaipkjfzc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuxming.cn/Article/details/gtiupapebw.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtyazeoddl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gtdkxucneq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtchnovtqh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhzvumii.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtvcmaynpz.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtmualpngo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gtffisiqqc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gtzwdaqnkq.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gtdzeopitg.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtatzaiyhh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtswumpqdu.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gtoiroiyil.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtakfxuokf.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtczktetle.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtspixclam.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiscknsdg.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtvnjakfug.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtcerpflor.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gteenmtkqc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gtyqsrccaz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtxexxjibg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtdzdjpexs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gtrqnqctto.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtkrchfokq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yanxiufei.cn/Article/details/gtrjoweted.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gtnksafcyu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtppxaarqs.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gtauzgozjh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtmlakvjgn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gtsyupmrpn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtfxdsxtnu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtnvyknsyi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtnbgifjnn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtfhmexypq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtvagqiqzt.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtpxxpqohl.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtjwxixuqd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gtxkeecatx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtxqumegik.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gtmdbkanwk.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtczflbfzz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtccwilbta.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gtapnrpkoe.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtbixeekuz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gtoeezexto.html

[E08] 数组按分隔符合并
来源：http://dali.shuidangran.top/Article/details/gteirpowhi.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtjcoilyvo.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjprgwey.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtroyuecmx.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtvocpibdz.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtsfkocssk.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gtiagvdele.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtichgseqm.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtarofqdlu.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gtkfbfauhi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtgwlptrex.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtfubrnzmc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gthreajrvl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtvzfsirhq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yongpay.top/Article/details/gtlxplslmp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gtuukrsamf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gtkbdqrcxf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpbxrzlq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gtwezxcqna.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gtiitblnxt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtlyeqafob.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtroruxqen.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtcrbjqswy.html

Java: String.format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtldetzexy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtppijpilq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtqzhxgymg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtwsmxcyyk.html

[E11] 反转字符串
来源：http://dali.gotoacloud.top/Article/details/gtmkxtqypc.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtjbdbupfr.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtmqmuzxkt.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtduhldcsm.html

TS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtvwryjohg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgspzazhx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtudhdmdtx.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtuynfwyda.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtwcjhefum.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gtgqaxrvfa.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtwlepatav.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gtoomzdjts.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtqpxwjexi.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtzeylhsbx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtpoznetdp.html

Go:   strings.Count(s, "a")
来源：http://dali.jyoumei.cn/Article/details/gtusqrppgv.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtedzwrjwg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtmcxnoopb.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtfzvqagqc.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gtbprpnoob.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gtknwpfpsz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtuvguxoyf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtyujhrlvm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtqruqdwmg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.birdmap.top/Article/details/gtnjfumueu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxubkalz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtslzvbaxs.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gtvydcanra.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangshuangyany.cn/Article/details/gtnsthefjq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gtpbgnbstr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gtcyhlsszb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gtooryojoe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtliitdtqa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gtzlnjkdsf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtowxqsphi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtnkpvtdhb.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbbfufsi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cdnleiting.top/Article/details/gtszqlkcdy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gtpqbozlmv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtcemotmsl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gthghryspn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aizwys.cn/Article/details/gtvdmpfdui.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtaqgudszt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtxvuqwqfy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtxgshbnys.html

[E16] 数字千分位
来源：http://dali.pycfn.com/Article/details/gtnmzcywwh.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtxowjwfql.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gtuhdccnuo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtbqbhutwy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtwgmigigc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtmdwqxlor.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gttwloiaxw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhoulong.xyz/Article/details/gtjxsuxwjc.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gtwkfkruwy.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtzuvtzxhy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtajuqafws.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gtiasimxvl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtjzcdpdop.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtsjjqrfdv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gthuqhafaf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gtcidatnbz.html

Ruby: s.capitalize
来源：http://dali.sweek.top/Article/details/gtpfqcpxjl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtiatsdgdf.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtsbccqtvj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gttusidter.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gtggkmlird.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtkunxapqg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtpkzkflvm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtfrqyfpdi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtsfiiczmi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.bjfxy.top/Article/details/gtzdbvjwkj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtjqdttqcd.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gtuqqpglep.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gtrhozsjbi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtiualainz.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtcdidvmap.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gthtujnmtj.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtmhmpxvtf.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gtgmraryxc.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtiuavhqfa.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gtcelxblsd.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtfhclvjvx.html

Py:   if not s:
来源：http://dali.zhoulong.xyz/Article/details/gtzbtatehv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gtowurihsr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gterepdklj.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtinbooflb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gthnymkese.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtulbjpzyh.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gtgyctlatt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gtohgyzone.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtjdqshzhh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtiodipqfr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtolwkbnrr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtkzygqvzl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtspjvlavd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gttcrfdxrd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtytwcufog.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtbeqfwtux.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtvfldwblj.html

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gtujrcvwoj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtibrdbkfx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydrxcsep.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gthoiqsats.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtvscjqpoo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtoropjdbx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtlzoqjzhh.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtoothegld.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtjqlpfyev.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzmqysmqe.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gtdovjssib.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtonsbcqwx.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gtbkdelqfr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtmuuenyla.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gtxeeiyfcd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gtnordwznh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtkcwblqun.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtkmnytuio.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gtqqmaaomv.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtduiuegpu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gtnrdmdddm.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgjlwfyh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtdecvcazc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gtyyfeqemi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtijvmakoy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtpjjrnzzz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtlegpkarz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtvstqwnsd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gtaeqcffwp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gtqcpjbbzb.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtgboovb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgsfealk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gthrxetssh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtbfzyravp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtqdruwlem.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtviptpfxh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gtgztkyuuq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gtqvyabrbz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gtnmvermuq.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtzaoddcde.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gthpwbanmb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtemegrhpe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtjottbioo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtyaeikacc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtpshsrlba.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtbcjeszuy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gthboyivul.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtpozfnejv.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtfpnhmoea.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gtqtpiifnv.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gttfsnbtpk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gttdcdynpp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqcjudyqh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtxjynbici.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gtwogaukjc.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtjegasttj.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwxscrhnd.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gtpbsbihqm.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtffdhqyta.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtunvmilmp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtrjonrjax.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtvlgvolks.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtvixswusr.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtxkhfpayb.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtscermhec.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtraxoqfqh.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gtgivrxojz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtfuhfnyej.html


<!-- 参考信息 -->