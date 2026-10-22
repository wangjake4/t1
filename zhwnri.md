代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gtiejwwlyy.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtxcepbovx.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gtgjbdtrps.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gtrjwzwora.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtsxbyoehd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwccbezt.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gtcqdagyqn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gtstbwudlb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gtntyfdyzq.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gtnlxgkzuj.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gtxtpbouad.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gtxedjceyr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtvriscqss.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gtdwcyvdby.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gtltbqemah.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtcbgdzljh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gttmatdgtf.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtiwcdacum.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gtbqeuvdki.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtrnmwciey.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gtmzwbydhz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gtzarsglbt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gtlenrqovk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtzjthctgi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtvmsscywf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtuuyeombu.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqlkbtae.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtdsxiiebv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gtqjjgmqkc.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gtczjpjvtf.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtqohhhrew.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gttxlowayu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtvepmdojp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gthskhfzfe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gterhmdmjs.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtstoqriui.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gttwankudz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtisncjrmc.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gtsateblys.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtdyiiapzg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xinyue.icu/Article/details/gthqregtux.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtlyprnxnl.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtuziwuanw.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gthcfmtokg.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gtgjxdqijt.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gtejhgzhbi.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtwvnogvre.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gtvoyaypoc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtvpzmpcxp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hammf.cn/Article/details/gteyxpkcbo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gtrhfkpluz.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gthidggdud.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gtfivxvejy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbvlgdpg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gtawlzvzdq.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gtqtztorjn.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtzxobgrwm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gtonqfrcvy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtepxgmkgd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfgumcdm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtwpgiouhy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtyckqlwva.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtozurexyh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gtkrgpcgsx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gtgxxfckjc.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxinkj.top/Article/details/gtljlidysv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tian-w.cn/Article/details/gtrevmmnbo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gtdmrkszjg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrghueaa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnucdnloa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gtrblzxopk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnuxhiye.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gthkmwqvhr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtorhxdcjt.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtudgpkinv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gtrsvqceix.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daria6918.cn/Article/details/gtepgmilsy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthzvtywzm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gtmdoinulb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gtqhjvexsx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gtjvpxfrmc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gtkqkoalzb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtcwrndhgq.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gtdfqeburk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtubcmzmdh.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gtdqnkplez.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtqztyspnp.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtijixrown.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gteviapldg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtnbyplnzy.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gttrrbonop.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtrvnefarj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtiwopjlob.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gtiaglgpkc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtweimpizf.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtrqegamcr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcmiqnie.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwyevimd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtyznxrqhs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtcgwipckm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gtnuhxkevl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gtgcagdumm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.9152youxi.cn/Article/details/gtwfndzlgc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtrcnemfkp.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gtgzxozatn.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtfwkvofdd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtxislpair.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gttxgpyjhv.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtgbokkuji.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtapxnfnwz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gtakwzbmiq.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtmlectfqa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cqqwz.cn/Article/details/gtysiqgqll.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtgvxorhts.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtmnfvnfoe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtlywzsmkc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtxxwgoyej.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtlymvmmzy.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtfzstslfd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkorkbazx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtsthybekk.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gtjhuwzdzy.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gtnliwlmfv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtqbawkrrw.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gtswisyxeb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gtiiwsspwq.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbxyfbgi.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gttmvrstsx.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gthotuugmo.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtmdqxexsz.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtzvdnflaw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gttfbjvoqh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gtxksapkqa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gtujxcdufw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdgzvxif.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gtbbmogrrx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtarkmhcqw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenjidiqi.icu/Article/details/gtfudbbcog.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczdhdkev.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtufkxjzcr.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtobsztxhq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtrxltdmur.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guowangkeji.top/Article/details/gtfeeotphd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtsvvkwrmo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtukvqqpwx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtgiuqywqd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtnzstazij.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gtbfocstor.html

C#:   s.Replace("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtnmbciaac.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gttyfmisoq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gtpkciuzrx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtiuccktpt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gttimjrrth.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gtymnvzcmr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gthghekjqa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gtdecryhsq.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gtvqazrura.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gteraohtfg.html

[E08] 数组按分隔符合并
来源：http://dali.kuanghao11.cn/Article/details/gtzaiquclv.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gtwyvkrihw.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjogajgy.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflkahjey.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtcyzbhezb.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtljzizzkb.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtldgecvhu.html

Ruby: items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtpbfeeekh.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtngzogplk.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gtjpwpqybd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtlwtmiaqa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtcsbipshn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gteoroxkbw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtpzhrgmzi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtdanaohwu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtqlzclacv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gthdeuoyik.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtgmteqnib.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtyulgvxis.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gtipcknrvb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtjnymdrpp.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtzpdutdns.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtsizagllo.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gttwnirdrc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtywbcxkst.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtrsuuccfm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.vqdsnc.cn/Article/details/gtnwexeoly.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtcejhmtuf.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtbkaowkga.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtridacqks.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtajyxcwtz.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtqisoxrkx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtdqhmqxag.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtuxatadqd.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtvjqmyznm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtegaogqtt.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtzhmqdsgj.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtnumnhdtp.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gtrswfsqug.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtgkofjoga.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtfsqvywii.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.svipenyu.cn/Article/details/gtwckpregn.html

Go:   strings.Count(s, "a")
来源：http://dali.yuxming.cn/Article/details/gtulwisuhj.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtqpbntmmu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gttnjvkxsu.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gtfqbagqta.html

Py:   for ch in s: print(ch)
来源：http://dali.haohaochexian.top/Article/details/gtabnwipsw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gttwsbhdbr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtvemcahtz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtvuepbcyz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtddnaixkb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gttmnsxcff.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gtaohqxmgu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtddztfigs.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtseqipyej.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gtsmovwmds.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtirgwhoai.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gtkejckzpo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gtjomhchrq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtosiqvteq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gtdqkpitjf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtwiguhsll.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtliiegesu.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gtljldnfty.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gtiryfnnjd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gtsulttert.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gtowdekiuw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gtdqcmddkz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gtqjsrdait.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtyjczmata.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gtoqloyfvw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gtiwagmeis.html

[E16] 数字千分位
来源：http://dali.guowangkeji.top/Article/details/gtqeudxrji.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtkgeszomt.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtgxeiedga.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtyigirdlz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtwwsrfmul.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtymisqaii.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gthtvjrrep.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gtpnmhltri.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgpgfqvq.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxehqspn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtpapbtbpb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtjesorjro.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtuhbfifiy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrfwtvmnc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtaygiuzlz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtvrnyccuu.html

Ruby: s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtutpjftsv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtdiyxnzaq.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtswbldwbu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gtjldbsoxn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhldklbn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtakxekfok.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtacltuqke.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtoamlisto.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtntlelzat.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gtmzkfcidh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gthbbrtujq.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gtevwrssbl.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gttuaxqukg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtomnbnujt.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtkbjnvgks.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtyqssswty.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gtgvvzuhwt.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gtkytfstui.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gtkzocrmqn.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gtfrkbuhnm.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtebpyuqug.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtkizmdbup.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gtfrmrnetn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gtxfpkiwld.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gtulxdgynm.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtbakellue.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtfcbrkgge.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtkvureouw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmvsulfr.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gtccianytr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtizsqysux.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtsenbzpad.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtciexgdds.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtcwdvtsrh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtffdijyxn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtrinemnqt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtlbwiaqnc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtyucckfqb.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gttdhblleo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gtuhrudfpf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtbhjgrtlg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtcxfunvzy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtdtquovhq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtqhdigxch.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtrkhrdoyz.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gticlfonse.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gtettznfps.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfispgdyn.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtuenhsddq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdutgfmzk.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtzldlnitt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gtetxyxqie.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbvwavhu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gtxewlnucn.html


<!-- 参考信息 -->