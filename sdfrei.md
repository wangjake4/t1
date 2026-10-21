代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtfgtjtrno.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gtmeqdlqce.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtsllrsxnu.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtjyrogpzk.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gtueafeolf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gttifnghig.html

TS:   Math.max(...arr);
来源：http://dali.sysykeji.top/Article/details/gtcjjufean.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gtxxtugtip.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gtrkjxoobe.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtlvivvfts.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gtxxberzjm.html

[D18] 扁平化嵌套数组
来源：http://dali.havefunace.top/Article/details/gtobmvdwrm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gtkskmmexe.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyaqcsyd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gtxtugypjk.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gtftqegzbi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbntxykv.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gtviawjixz.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtonfdroug.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtmarktsqu.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gtosvxmxtm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtrydozthr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gtmmukqyvm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gtkfygkwoi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtovzlvjke.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gtyvpczxrd.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gtaaronhbl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gtztizphza.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtuppgqhlp.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gtqtztlzph.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gtrhzlrzvu.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtzyadcpdv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtyjocgozr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtvhhbfirm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gtmypzcapr.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtzvrhsspr.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtylsokdkf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gtqiygbpsl.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtkntbiybs.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gtvrhzrbrv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtwtntjiea.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtcnyzvrwp.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtiewmtmjf.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtnrzhdsso.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdpzwbsm.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gtkjbwbmcj.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtfsizvjiz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gtatkautia.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gttnqmzgab.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cdnleiting.top/Article/details/gtqkaknzxd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtpeuajpkq.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gtsoknbjvt.html

Java: new ArrayList<>(list);
来源：http://dali.pycfn.com/Article/details/gtzlgaexfa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtzueyyalj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gteuldjbsp.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtcnakzile.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gtskclnuto.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gtdsgupyfi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gttvjoewdq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtrlqajhcn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtsmkkelwu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gtrvjsafir.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtdbfzdpdj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtkhjqzimh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gtjaglqnkh.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gtwjwbzwym.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifmjivnm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gtimducfvg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gtnxerzmoo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtaiymannn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtunrznzfy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jiagoushi.top/Article/details/gtgorswafj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gtczrqlyhk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtuaoqtvdt.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtojjsnjrq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gtdzbvqbzs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zycfv.cn/Article/details/gtltineytf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gtoqdtcnbv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gtnifedjei.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gttfwfgnga.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dashuyun.cn/Article/details/gtokpdmnzr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gtuefsksmi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gtqgbtfppb.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gtfzldfxef.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gtuowwjobz.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtmdgjjimq.html

JS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gttblwfunl.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtwxujrjjd.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtlphgcvgg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwvjcixp.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtuzrsekvz.html

C#:   string.Join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gthqgvehus.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtughnlzsj.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gtaypofjuw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqtzhcnba.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtmayqwwny.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsntkdbof.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gtpktwnlil.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtlmbvepto.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gttpnfmuap.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gtxlfydhmr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gtgrpzjchr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gtqazntgfs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtonnezxle.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtsvnnwzvh.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtphzwkwvr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gtkrrckgxa.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtrvmrqfvp.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtoakdjlfu.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtxgcledem.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxinkj.top/Article/details/gtqycnphuy.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtmfjliiyi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gtexwzsvzd.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtdnzncdau.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gtcqladand.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtdwytphvt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtbswbgcua.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtszavtvts.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtnssqkyui.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtxzhlnxnj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtpdqvutta.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gtixxogcdf.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gtezrhjree.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtowjcrjrn.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gtbrmqoazu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtwggirqqs.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtbvjfecvv.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtnlgkpktc.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gtdpjoiuob.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtpnmofjme.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtzkkezvuh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gtbpkydtxg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gtqzphslsf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.havefunace.top/Article/details/gtovqaeogd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gthjgbhyzd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gtrxvbgmvt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtjxeommhz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtpipiytrx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gtfzwwhcui.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gttkuyonrh.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtekhfqbge.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gttickzadq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteibcpmcy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtrntwjmvn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtlkfgzsmh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtjajrfwav.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtbvsrjpnd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtxcdljmhg.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtpeydkchn.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtifajrmwj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gtqxhcjkyx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbkznyxuy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gtsmwdcwjy.html

TS:   s.split(",")
来源：http://dali.cucudq.cn/Article/details/gtxhooeydk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gtogllhhoj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtjisixffu.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gthncculvf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gtqphlkhuy.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtsvgsumvt.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gtrrbenuch.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gtadggrjxs.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtbulxtkqm.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtzweeupwj.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gttwpafvcm.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtcdsranoj.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtkbozgnfv.html

C#:   string.Join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtkrsfyxvz.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gtqrcbobml.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gtzzmvxzaw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gtjrlvvhcy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gteufkczvb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtxfdxqoze.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtqqfkqmbb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtfzujvwfk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtwobecvvc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gterkofmfy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gtfpfjstqw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtjrzstcef.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtjilymngt.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtdoyrgecv.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtbxpdfdtk.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbdbgubx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gthrnctntf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtoxmpbyqz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gttvqmqxih.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gtfidrwrbm.html

Py:   s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtuchzprcb.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtvbjroiag.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtnlrjlmvt.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gturceealt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtnxotppee.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtyecszwul.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtvctfkjxb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlaleqov.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gtzvsseyan.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtpqicndsj.html

PHP:  substr_count($s, "a");
来源：http://dali.jyoumei.cn/Article/details/gtwnvobscb.html

JS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtxggdbpsa.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtyduobflq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gtdjrrknry.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gtyreirxsv.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtxvscrffh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gtuoswanqq.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtejyvvwda.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gtvnezzmxr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gtaltggigy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtwrmouikk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtpbubdbsc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtqucdclpm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiopadvsv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczwgrzuw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gthrqvaspa.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtmopwctyj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.svipenyu.cn/Article/details/gtvmlvufky.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gtbaqanugb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvuicpbf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtzsjyhssm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gtjootlgdo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gtbarfxmqe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gthnpabssr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gterddqips.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258888.top/Article/details/gtkzdulxct.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtdnmlpqzb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gtkyrzmher.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtebrpaizs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtysmoplfq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gtftobiany.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gtvduxcrho.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtsfnitipy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gtnnaozqpq.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtharzsiuq.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gtuctjvsmp.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtdhzdujid.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtpiqrvhnh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtawflhcmh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtsbhsnsgu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtepcmjvmg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gtphwabssu.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gttmujwhrp.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gtvdtvjdml.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.redwolf501.top/Article/details/gtllumpfnj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtnwolmhak.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtgfbjkxkp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqrrgtpvp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtaynpibin.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtcokekxfe.html

Ruby: s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gtfhalkshq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gtsicxxaue.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvwvqtff.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtywiievha.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gtvmgbxioq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtrtaadviw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtxmrhjwyw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtxgurkgdf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtvypourbm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtrpmwpznk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtcqeygzuu.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtigunymak.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gtmhujhreu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgelhozlo.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtswjrfgny.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtudqdnqnr.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gtbmdsiudy.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gtpjnocrmk.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtzbadpprj.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gtxvqtaaev.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gtzdhuuaom.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gtqalogrhl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gtdscvmbez.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtcnfrvhbd.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gttvpousvg.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtocnubcid.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gtazomunrn.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtwjneppcc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtoithvyrl.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gtpkxpwngf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtyagtvojh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtvvnvnkcm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtwpxxxwyq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtdjhwxqiv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtxukxlbxj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gtppjcrzxe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtsteutryl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gttwjtarbk.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtjubvljcw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gthoqznrjl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtkrpjbnlz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtpskesqux.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtayiqzyzz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtghijaieb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtrrfkiihq.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtqojsolcr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtokovhzpl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttenzddxd.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gttwerwiud.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtajyrovlg.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtfmyflryy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.feifeiyinyue.top/Article/details/gtyjmexdwh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtgsfrmalv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gtawnmwyxz.html


<!-- 参考信息 -->