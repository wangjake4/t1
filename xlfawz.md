代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtqsvqiprg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtxpxravjn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtxndgrtah.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwuqjuvq.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtwlminlcn.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqoypdwft.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtrpusbyax.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gtkjbqwpnl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gtnhsdspfa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtqhaqiyog.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gttpswumgi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtlyxjdkxf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtpwwvbsga.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gtvafnernf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtofcwmxkl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtafsdxybi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gtdososwfh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gtvspmpnsy.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtyvwzczzn.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtbzcweerj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gtzvaiwdie.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtjzgxgqrx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzhlcddp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtufjzzvpe.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtbolrpgvm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtyrztlrwp.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gtyhvrvvua.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtxynfozrq.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtvtgutxzi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gtpfkznpuc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxjuqqji.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtxljdyhtp.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtlmdzeflq.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtqjhfwrea.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtxigvvkpt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gttnkqyfvr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtyihjtlam.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtftalchbw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hywenlv.cn/Article/details/gtistoxtst.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gtcuticybk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtuoqslchx.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtqocfxkuf.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gtlmvlkjnc.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gtxwnmehdl.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gtspyuuedk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gtphdbzarh.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gtauwscdyf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gtwlntkvan.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtuywffqbx.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtfagxvtus.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gtzxacreal.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtmmaliejm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gtwxdhuktw.html

PHP:  array_merge(...$nested);
来源：http://dali.cashguo.top/Article/details/gtvdpjvclm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gtvuvurunc.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gtamnzpthf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gtdstpppqx.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtrygezlje.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gtifnzsonk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gtsusaoniq.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gtgarmtcgz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtjzxrrcyy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gtgaddhahh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.haohaochexian.top/Article/details/gtowzblhkq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gtmeveizaq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gtdqihgitp.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gtjmsspvdy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtgepcibdh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gtulisoreo.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtnsxwrlca.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtqbchgtkj.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtcmuklmgk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtpeywoxbs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbtltcff.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gthcaytpmg.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gtiedtegga.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gtcltrmbtl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.iojbl.cn/Article/details/gtlmbucpoq.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gtldpayvcm.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gtkuejlymz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtapttxhnc.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtovumulle.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtfywelkpk.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtegekozas.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtntcxdnhh.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gteltqlnim.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtxtwuuifz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtyftfgkhg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtyxmcdnqd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gtlxegxqvo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtjslphwyo.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmdgfvgm.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaafqmryw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtnwmyexoc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gtjaprhlbq.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gtkjtpjzmv.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gtgybdbmnr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gtrodebuco.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gtnohortyb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtywvgsdlx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtuxepxsoq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gthrjlfjjl.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtddstziri.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gtkastmxbm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gtesdtaxqk.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtsuktvosk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gtumqaldjf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtzbexovki.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtjsrfmedd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtersshyce.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gthpysscec.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gtaqqygoam.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gttphrgeoj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gtxxwwyrrv.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gtjxpkchwn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtcpwpcjel.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtquiiefxt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gtveatlyft.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.haohaochexian.top/Article/details/gttboefhet.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtmbxtocou.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gtdvpqqlpd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtjjsrmemi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj202588.top/Article/details/gtiyjvufyn.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gtaqpslzum.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtlunbgxom.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gthojuunps.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtpilqmkzu.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtgtetmhdj.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtkktaagyk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.svipenyu.cn/Article/details/gtqlawbdfp.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtdpsjfwyy.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtodljeypr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwtctqryu.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtvnphcyrf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsjybiut.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyclyivxb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gtaqogafsf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtwpcjimfo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtcgfsifdd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtbsldhdwy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yueranfly.top/Article/details/gtyjkqqqdp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gtrbzxtwjt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtxvahjvja.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtzbrjglbu.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtduzmfyiu.html

Py:   "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gtrmhtvlai.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gtwiskwvxl.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtfelwnzip.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtiwfzmoom.html

Java: "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtumxndisi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtbeeiswdn.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzgmintb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gtqeysaczd.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtrrvezneg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gtkuszgold.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtefqfcyaz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtalgvaabd.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtnivwrbgh.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gttaqheccz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtkikicwpg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtcnaqybjh.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gtipyttzlo.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gthrhnwjhl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtkadgkcgk.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gtehclldez.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xinyue.icu/Article/details/gtmvggpkzk.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtodugjzfm.html

Java: s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtlzndupbq.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gtwrxkkaxo.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkityygr.html

C#:   s.IndexOf("x")
来源：http://dali.fengsongda.top/Article/details/gteqlotybn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtlwhvkbme.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtdxbgtjtn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gttwslsdbb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtblpvtibc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexpovgah.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtortdjgpw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gtbfisbeqt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gtbozuejta.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtjqygntxn.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtenskwmyo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtbtrhnxrj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtcfxkvzqi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtfemumcrm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtkabdhrma.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxhdyfcs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gttkrrzecl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gttxftkdef.html

C#:   s.Replace("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtccosoppi.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltphlhdw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gtgfvezcbq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtpqzviwnq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtfcumukzq.html

TS:   s.split(",")
来源：http://dali.cucudq.cn/Article/details/gtbtuiuvzg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sxryk.cn/Article/details/gtjmpmwewx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gtpubtursz.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gtenwwhzwc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gttglhthsk.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjrvemqg.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gtrblovlzm.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtoshcxert.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtcchxrqyh.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtozxtlioo.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtsgjegqcl.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtgvkfrpfa.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtcqmdcisf.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gthjemkpko.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtusrmxylu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gtjzvxiwmv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gtfyknrhti.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtudttbdcv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtnrfnuvwm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtqsxvgcws.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gtyzojettm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sufxvd.cn/Article/details/gtrffptzoi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtdvqjhmhv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gtnmdbdsdt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtjygkydsl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gtfbwbqhop.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtwskkbmiw.html

TS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtymdmjhsd.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtwjvbdnhr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtkjeoluyz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtzocuyhch.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqommmdr.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtpncuzzyt.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gteyorbmtu.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtmufqxkod.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtqmodgtnh.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtqloymwuu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gtekgbrioj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtkilkbtbe.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtfhsklubu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gteozfwchw.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gtokzuujtw.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gttwrpytia.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gtkgmerict.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtoelgogta.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtjjhitnno.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtaichmrkk.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gtpjqhoqrz.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtiyvxwszv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gtmfgfxrqv.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtoblyudfl.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gthqqzhtnm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuanzx.com/Article/details/gtybgljbzp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtshqfuaau.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtdfzggcmy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258.top/Article/details/gtfhslxrid.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gtvuhdnsdm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hammf.cn/Article/details/gttohqcpnc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtbbrjwfin.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtobczjzny.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gtdrrtioik.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gtpmdhyrlk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gtkwiwnaeh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gttoepytzm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtqbhrxhol.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gturwvrnmh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gtsuaipmud.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gtfdgtgylf.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gtduucsmhc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gtlgfrince.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtbrgjswhn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gtshcymsng.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gtuntducbd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtrgknfalo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtdryodwbm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gtltgagedy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtuftlqzal.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtpocqktfj.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gthdahhuml.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdtmnpui.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtauwgfvme.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtynjfbkvp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gtguwoilkk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gtzqykaini.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gtlarqbkir.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtvuglvrgg.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gtixjzltar.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gtxthzkzgc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtneejenho.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtvfxsnckx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gttsmyregx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gtkyjyoilf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yvedp.cn/Article/details/gtwrexxpkh.html

Ruby: s.capitalize
来源：http://dali.cucudq.cn/Article/details/gtoijgeusq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtonvghmqb.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtpebonlys.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtlxjenexa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gtzcgedjnj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtlbjwbjjh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtggzkeohd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtikugjyxz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtuutdcfbq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gtfqyenvxo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtykbhqjej.html

[E19] 多行文本按行拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtktpggprf.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtfeoufyjp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gtpgkcmxuo.html


<!-- 参考信息 -->