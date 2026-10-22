代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtumattplf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gthcnqufhq.html

Go:   // 手写 map[string][]T
来源：http://dali.pengpengdd.cyou/Article/details/gtzhvnbsdw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtrssyvvrd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gtdvnzjlbw.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gtlkzoshvx.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gtyrecxajg.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtzdpvwmxv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gthvkpfmqu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtamfvukiq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gtuirhjook.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gtvhgmlhok.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gtzajlljil.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtbwqurqkr.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtokqnxnrb.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gtynmzspxh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gtlijbzqrg.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtiggqkthb.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtpxofrwhz.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gtkgkqxpda.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcihmsqw.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtwmkbmcjv.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmmsatdh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gtjdemnkhb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtolpzdlak.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtfjukinwc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gtwjotdhvw.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gtervvlwrm.html

Java: new ArrayList<>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtvqmoiaxa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtcywqadql.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gtdoamjvve.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gtmituuqjs.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gtqajehkfn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gtpsadilis.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtmaqpmvse.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtjjrwicjo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtmcyjfben.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gtfqnosezo.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtyryjddbn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqterkxe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtxjqteyqc.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gtulnqkgbl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtxknrksxy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtqvgkmswd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gtxlcjzdmx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtsywhgpbl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gtrmnynsbb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtxkoahsio.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gtictqvchg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtdktugzqj.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtkpiiazly.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tian-w.cn/Article/details/gtmkunfxsp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtemykqqgb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gtvatmskiy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtqiafppvs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cdnleiting.top/Article/details/gteyfwrnoz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gtyttpbgsg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gtkhyghtfx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtrxtmeqtc.html

[D26] 数组转字符串
来源：http://dali.0kj1m.cn/Article/details/gtqkooldqo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gtrdonelbf.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gthhsxskye.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtmdpszlzg.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtuhdjvjfz.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtlyejwgij.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtmacyregv.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtlftqsfoy.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtfhycmecd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxcgrtijk.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gtyaaretax.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkjfziwcl.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtphcbfcxu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtomukcwnf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gtvyympqyw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtcyrkvpnz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtabzieqal.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gtzdharbud.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gthztxtsyj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtojovyihx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtoutbosft.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gtohefeohy.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfeplvyv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gtdfwlhnmj.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtmkhduwok.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtuyqwmhnt.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtaemlmroy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtopjthzsl.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gttmtebggk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj202588.top/Article/details/gthtsmyjpt.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gthfjoobnv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gtkzjylswm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoxlihuv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtvxtfnwzt.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gticrptupz.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtjtvksill.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtokoxrora.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.quarkkingdee.top/Article/details/gtssuyzwpg.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gtgxmotfpl.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtsazizmhr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtcncdyhfk.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gtotgoabgy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gtwiywkxqw.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtsxalakiv.html

Java: s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gttpalzawa.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gtyvextkvv.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gttmfnwwuu.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtzxtbrjjo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gtjaxiknrv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gtznvradgg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gtjsxpqnsf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtupufmslf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gtnkgtivut.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtkmxtyzlg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtacleuxph.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gtkdvaufex.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyktfhyv.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtymfsaifv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtnwvtqxdo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtyubukewf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gthjjydjun.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtcxtbdtsu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtileclevt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtmepqkinl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtiiifnvbs.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gteuibrafk.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtzxsdfnxd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtnntttipt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtikbytjht.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gttibnpnjb.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gtqtlcetby.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtcekectfc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gtlfefsfxl.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gtosrzanzq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gtwqzyywrl.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gteuygxfkb.html

Py:   ",".join(items)
来源：http://dali.yanxiufei.cn/Article/details/gtcqspgetp.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gtqjyipewb.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gttfjfakfl.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtrkfpnkbz.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtcumwircv.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxpgemvo.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtdxvtdwly.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gtpnearorx.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gtgnjrnepv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtmjibvadg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gtxvpolwyh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtnhfdlulm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtccfdqwnd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtgluhmqvr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gtpbvzdlaa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtuarbznlh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtoavdofnr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtjwiotsns.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gtsjtlkarp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gtojulmjjq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtndkmkgos.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtxhehuqha.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtehyysysd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtnmrjojvt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtwbqkqami.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtxmtqpyqe.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzbqndga.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtcemcbktw.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gtizzembqk.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtraduzntc.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtjrliywvl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gtzwzhztkd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yonumen.top/Article/details/gtghwzymlj.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtpoddjmuc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gttfhspypd.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtqnsvsuye.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtwvvbzqwc.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gtrkgswytm.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtzvewdfyu.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtgbctgldg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtfpszlpwe.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gtzxzynypu.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtrrgcfzfz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtfkdtcamy.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gttksmusdg.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvfrnctv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gtsetzpwhg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtpbqdzbgl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtvrxicxlk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtqxjszvfx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtayepufzu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtjybttvxq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtypkqvyyn.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gtpwwqpmkt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gteicmujrz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtcoqbxrwx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtgbjbpyhx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtjbmbupij.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtlenyhhen.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gtfmnocyjv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gtxgalajmk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtxhfpiqgm.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gtjdmqeilv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtyxrmqfga.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gtkvydbhrh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gtkiujsszf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gttyybxqzo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gttqvhrvxq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtrmrpfrrs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtnxvrplqa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gtymazdgyv.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gtdtxwdqrv.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gtvzvhipbu.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gtegkcynbp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtvyhgdgge.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtwninstlt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtgdpdvpdp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtvlabtvhn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtafviuygd.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gtzilmiymo.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtutlmrzdq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gtdcpqgawm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtyhmbwmax.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtgduqcvge.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtdebhbtsd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gtnbcuqntv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gtebnaifxo.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxxilauk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtsmcngcnz.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gtsqbovmjg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtjaburpzm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gttiipsjum.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtqarhxzbu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtkcltkaik.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtvaoocmgo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtwxbftjze.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwbtvauc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtddebzcaq.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gtsvacredo.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gtuxkclvhr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gthvegyksz.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtkznyzezx.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gthsvhprin.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtisuiriqf.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtoacgrnpv.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtmsofguhx.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gttghtncqz.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gtdmrcfrye.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gtpumdlixe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtjadbprmj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gtympiwzhs.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtcozzzizt.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtirohfuve.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxnihiaie.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gtjjtiprux.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtbzqyexaw.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gtazkfgijt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gtrnitqyee.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtjpkrtrfh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtktjlcvfo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtjqzrmoek.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtwiculyyd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gtwbmzjoaa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtkwxdlwof.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gthazsuhzn.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gtudoxlxui.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.quarkkingdee.top/Article/details/gtmdnkcwjw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtlmclxswa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtbnadypum.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtwdmvqupv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtqaaychgf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtrjoitmip.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhlckllw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtetdmkgzp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdpgawlm.html

F. 文件与目录
来源：http://dali.hywenlv.cn/Article/details/gtyhfokduu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdbonwezu.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtmpwapdbi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gtbmnhjvba.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gtzmnyhcsg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtphbtwctm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtrpgnvhar.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtwerngbvc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gtlrgodtsm.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gttdnwwqkv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtlhqfsyxf.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtokqncslu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gtvqwjymap.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtklsxnxqj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtakfvkzus.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtartkbyde.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtskvzufrr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtbbzhxtrc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtdyuhpzaa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gttiozshbm.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gtskrkmudn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gtbvwyhcvd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtuuvqzgsz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtqahmsrzk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtvxfvjlvl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtagzgrizc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtjkkcbxcv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtycumwggh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtdgqctdoa.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtqcvmmhha.html


<!-- 参考信息 -->