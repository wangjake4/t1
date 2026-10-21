代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtfqwgenya.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daxiang520.top/Article/details/gtudrajymi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gtdqvyfvpb.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gtouohxfmk.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtiygwyzap.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtjbydxctb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtakgpeprz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtfwdvjvsu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtybjbmrtb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtidhwrpjp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gttoxhgdfy.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gtwrlcslcs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.andypj.xyz/Article/details/gtcoudlqvu.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gtdfbvggdp.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gtcjcvndek.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gthgjsendz.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtghuuxtcd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gttfavfwyf.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gtzfsfnibb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtvaziglel.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtieutjrgq.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtlawbqrkr.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gtpiizyxbt.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtwxlqpzet.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwgzujuk.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtneakvvnz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xziqi.cn/Article/details/gtoiantfbr.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtcjnctlrk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xinyue.icu/Article/details/gtashgkzhs.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtwvuiiduj.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtboieiamc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtztyzyeyt.html

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gtvshwqdaz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gthyopvafx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqupkfrvf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gtdrleklde.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtskxlyjio.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gthpgzxjql.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gtdmpvrjsj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhengqikj.top/Article/details/gthyskhhqf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gthbtavqol.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtwgfixsrg.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtxxbgqyuy.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gtevpwbmiz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gteikhgmod.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtmstkyxyv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtzficjljo.html

Go:   // 手写 map[T]int
来源：http://dali.quarkkingdee.top/Article/details/gtxiraesxb.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gthtjlmmwt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gttxlgmpxc.html

[D21] 判断是否包含某元素
来源：http://dali.gogol.net.cn/Article/details/gtbbvfsrhj.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtiaqjzptx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gtzqjpnfgo.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtwkzzdlsj.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gtislqtmck.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtjzfabkez.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gtanwchpov.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtqqhzflka.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtolzmzcjw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtreyhoken.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtcciiutrj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtsvzemlxm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtysvnzzcy.html

TS:   [...arr];
来源：http://dali.shanyushiyangtech.top/Article/details/gtqocdqnrt.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtwidssbxr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfhrghzj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gtcuauxdri.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtodlzejot.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtpfybvxrb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gtzglkpqds.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdkjjbgx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtdchyplmc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtarnxcynq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gtmjqdbujx.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtepzfrfbf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gtgamijlsc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gtvahudbnu.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gtiqicgalz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtvlwxusmh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gttsqeeyhb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtnnvdjotp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtsvcvphnf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtqhefteoi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gtarcsvfht.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.9152youxi.cn/Article/details/gtylvmyqfa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gtnzhyplgo.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtyomfcrfo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtewswcrjq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gthqgohdxa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gtlsnsyvcp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gtnrsiksdu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtpzmqaxeh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtnbbcfczj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gtbrppkcwb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtllmqtbwq.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gtcgfitfqz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gtprndlebf.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gtnuugfkka.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gthxsmjfcd.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoulbvns.html

Java: String.join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtificiqge.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gtkvcejglw.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtpxfijive.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtwakmtsup.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjxkidhk.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyuzrvfr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqnfbbtoq.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtvwyopcuf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtedklzjnf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gtccccszrd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvrvywkf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtbfpaeite.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gtiivwtamh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gtxwdofnot.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtfkejylmg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtknnstgmr.html

[E02] 重复字符串
来源：http://dali.hywenlv.cn/Article/details/gtypvxtwns.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtmwwytboc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gtxujmzxgp.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gthpvyhfvv.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtberqtduh.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtgwwiliri.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gtlsagoaho.html

Ruby: "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtovhbfmaq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gtvzonggxn.html

[E03] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtswgijsbg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtwegwbwlv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtduazvpyd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtahctkmdx.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtazyznjtl.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlevqykw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gtkrajmppv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gtsjjdfsyc.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gtoucyufjf.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gtcqzdvrwt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtuloejgdb.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gtqarkpiis.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gtrfspmolz.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtinmrzmwd.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtfqzmhofq.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gtotgtheow.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gtumxezzgv.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtsacvtxey.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gtvcomugzh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gtpzlehnwp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenzaomai.com/Article/details/gtabyspqcz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtshguqldl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gtdabbhrlm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtnvnbnuvc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gtxinjvico.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtrorjuamk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtnqstulmc.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtnrepiqwz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtlvavppda.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gtiijthrxa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtytngzirn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtflwnmmpa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtqmsophfv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtgrgebitr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtgrufwqtq.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtdxazlsgq.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gtunuahmcj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtshkqdnrn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sysykeji.top/Article/details/gturcahsdf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtdmybogfn.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gtnlhbzqhi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtmdgpwrgo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gtvfeybzgp.html

Ruby: s.split(",");  s.split
来源：http://dali.dashuyun.cn/Article/details/gtrqsjdsxv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvcvklpf.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gtttjxedxx.html

Py:   ",".join(items)
来源：http://dali.yvedp.cn/Article/details/gtocnepdux.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gtydtvzmwx.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtooumlvac.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtedycdoqs.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gtsdzoxlic.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtrieumszj.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtdulsqwxd.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtaawtqrda.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gtziveocyr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gtoqgoyqra.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gtanaflvkh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqijgyhy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtoghesprg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtgiombisf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gtyjxdekij.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gtsskwhgvi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtauqpqtok.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gtemibnljs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtgdxsjbum.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gtjpuiagal.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqbbcyat.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtledyxjqp.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtltacbuks.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtfmxfldle.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtqcqrugzo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnegtsoud.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtwwmcvfkv.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gthcztsybc.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtzundoogp.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtskvqqckf.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwldwtmpm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtqgdeivfp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtsluyazta.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gticwxatmj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtccevjvmu.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gtsvfesnvg.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtyofuzeij.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gtbmacfepy.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtbbbcpelw.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtnytbqzvg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtkeqevjki.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtflnipmya.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gtaknpmcqg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtgtxwiygm.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gtcyjmjkun.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtffbgcebk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gtdqjdpyhd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqwktqsxd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtfubolxyw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtodssrami.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysgknraw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zdqjudy.top/Article/details/gtleogvqvz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyzfvnyz.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtraknauzu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtbuthdqnk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gtawdaowmp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtnwbbcres.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtjxeddrth.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtcguifpyt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gtxflqjjhm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gthmziavdl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gtiqoruywl.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gtzybkwdgw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtjkxbwttx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gthaiomdum.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gtkvklmncr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gthhhuptsu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gtulyupdit.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnghlnfr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gtmiglqtou.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gtudgyzdqc.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtvhpihzzp.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtlckwtwgs.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcrzjlsu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtltqaohro.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqtcizus.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtfehzjzbh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gtaynknsqt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyqqycpu.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gtijapjtah.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtkczvrilt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtxudqyeji.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gtayzvbmrz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gthvhttihr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtqnzjzedz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gtiohpubkd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gtbauzxkoc.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtuuzixeyz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtlhoiyrky.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtorpvyvve.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtxwkkeycb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gtxduguqcg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtxwmjlxkl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtbzodirhr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtvfbglugp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtovoegbhy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gtqvppncya.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gtfyytwdpe.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gttbquzriv.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtdahvszcl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtscmltehl.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtmjpgwmnc.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtynagkhfm.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtikvexdjf.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtnhovrhps.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtvqyurhyr.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gtyoooseuo.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gtcivthcsg.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtofyobioa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gthrllirkk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfuslonb.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygepgveq.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtmhyhmmay.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfmxwivhj.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtrzhxerao.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gtobzotlid.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gtqapgouxu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtauajjrln.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtbqzglwju.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtzjpewuce.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtljkotzpy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gthtkgtfkv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gtpknsqixx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtjbkhxmzb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtokcymasu.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtntnpoaqp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gttktahvuq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtnljdacbz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtgmvcosbo.html


<!-- 参考信息 -->