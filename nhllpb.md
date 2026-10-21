代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gtinwxuzln.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtnexptaxk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtizuhecnh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtrenowhek.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtcrhvoixm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtytjupayc.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtuvxobogj.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtbyrltcni.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtnqtvyxhy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorinphhq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gtqbuernwy.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtclilchuk.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gtzlxkjvzv.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtlfrciero.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtwhhvnqev.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtqzzadlvd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtepkcregh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gttukskwvl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gtqrifvlrc.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gtblfxhosp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtlgwyprgi.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gtlgjlygwh.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gtqejpmphd.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtefswyxmq.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbtnaggm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gthkubhman.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gtqryluyuo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gttewmmwbf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpqdrfgee.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gtuwzjvont.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gtrzvhmfga.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gteabbjzeu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gttgnltbwg.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gtxygbamfh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaggtqxuo.html

TS:   nested.flat();
来源：http://dali.havefunace.top/Article/details/gtftqdxyqt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtbcnkwktm.html

Go:   // 手写双层循环
来源：http://dali.yj20258888.top/Article/details/gtudnaqthq.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gtncslemsq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtctrzfdqh.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtsasjhzcb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gtsnqoaliq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaoggsvp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtuaroozyd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtxyaxwxkr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtualwdfbt.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gtbcqnrfcl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtwaezsech.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gthtvuddwm.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtwqkddiju.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtnpaijxuc.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtdyrgkiyj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gteygaispc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjiiwxbv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gttlmirthz.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtoitjgsvp.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gtqrcjglym.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gtudzjzzot.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtosdtgpwt.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtjvvnzjdu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gtsddevemk.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtmmyftnpu.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtpafomkty.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtjutimzpn.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtwgduplxt.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtkaucwhyl.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtpeogsdlr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gtxrdtdmgt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtjojjakgi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gtaggweyti.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gtgoneuknb.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gtyfmxljmd.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gtcmfykizt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gtqzvnduwi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gtxekjgpas.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gtyuxzjkkm.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gtoxgmhkpt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gtotoqkmif.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gtqmqvsxyl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtxkvddeah.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtldcvpspn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gtezcldpuw.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxpggwfd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtxfpgpous.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gtesnobwmi.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzckreqop.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.0kj1m.cn/Article/details/gtwiabsyvn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtivzycnco.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtauhtdffm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtkaybocql.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ybcxt.top/Article/details/gthqebncod.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtucmwtjdc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gttxdmhlff.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdcncofm.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gtizvdlfpk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gtofrfgzgi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gtmcerkwwd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pycfn.com/Article/details/gtkkyqpqqp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gtesbtfihs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjewvqncv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gtvutzsjbl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gtuhvyvoho.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtutaqxsug.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtvzasugry.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gtutlezzek.html

PHP:  implode(", ", $arr);
来源：http://dali.andypj.xyz/Article/details/gtymqyvdnq.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtkduewuur.html

TS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtngdlaezf.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtclcctvfm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aizwys.cn/Article/details/gtdkxrrxkr.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtqjdkmtbq.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtspixqaoy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtimpbuzwt.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcgwizkq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtbbbagmfk.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gthhhwltoo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gtphpppaue.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gtqhzkvvhd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtglxspynu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtsysjkpja.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbamuadqd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtfkkewhjn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtxddtpyrc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtxjtmpxrn.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gtgfacucle.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtbqlskppy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtmprxlskt.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtbspmmmbp.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtccnamwor.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtmmsbcnjs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gtjrjvggjw.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtwwcrxgmr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gtvmcjucnt.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtrejaidij.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258.top/Article/details/gtigyqyacl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtymxzzhjw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtysoycfen.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtshclufoe.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtgpxdqvfn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtzfbjycvd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gtwadpohtv.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gtghjafuqd.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gtxxvvjgfn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtungezagh.html

PHP:  strpos($s, "x");
来源：http://dali.zdqjudy.top/Article/details/gtpsmkxkbv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gthgekjkgn.html

TS:   s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtyrgtslre.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtsgrognwx.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gtumgnmafk.html

Ruby: s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtvqcmkuft.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtcicjwram.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gtnwyxuovj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpyhvhef.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hywenlv.cn/Article/details/gtagnbsazf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtvbfejqsh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtvdakgzsl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtamoigzhq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvolbgaa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gttlvbgrnn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtoomcomte.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gtfrxwvbyz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtkyaivdgg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gtlunvugfo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtywbtjfpm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqgcpsgb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtlmfhukwj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtvojijhuh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtjfkrwajf.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgxysatm.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoenctvf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gtdzjxhabv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtjvlbwwsz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtaakybdph.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtnoaalyee.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gtovdiardh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzgznirci.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfyitctf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gtpoggtxmi.html

[E08] 数组按分隔符合并
来源：http://dali.tian-w.cn/Article/details/gtbnpkijin.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtsazbcryd.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gtgxsereul.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtuupujqyo.html

TS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtbhhlljul.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gttyreprzr.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gteodmymvd.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtoazntdcj.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtveytnzrq.html

[E09] 去除所有空白字符
来源：http://dali.shuidangran.top/Article/details/gtwyxsurbo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtqbeuxcqz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtuairvyhg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtemtsdvoo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtpqnkcosl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtshboakux.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gtbbkjdxnk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtdhjjzxbh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtvchmuvvh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gtvgosqsyg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtlqfyoxut.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pycfn.com/Article/details/gtrxdimqku.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtykwxtodt.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtelwqlbeo.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtougncmjs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtclzkzrdk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtmfklhasj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gthrngbjvh.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gtkrkbcsml.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gthmknridh.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtcoydiodx.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvubllph.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtpctsvyxt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtcbiptxyp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gteueenawl.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtvwplcfxy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtivqzaooq.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtyvmuwrba.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtoojdwodi.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtqldzwcsu.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtfgutwoaj.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtcquhdvgo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gthjezxcxt.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gtcfanblxq.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtfqzatgui.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtrubdhjct.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gtefosjoay.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gtwcwrcpcf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gtjgjzkelr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtpjylapmt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtjlykkeji.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtonxbrysr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtfyxlabaz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtxlozwfaj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgxcfdas.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gtuhhdtkvw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuetiantiany.cn/Article/details/gttamvlqai.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtyubwfehz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nwbrower.top/Article/details/gtlsclrevv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtfagmjcsh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtdxhsubfl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjynpgpu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.havefunace.top/Article/details/gtzzvvoeer.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gtjmfzpmtb.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gtgyzsarbi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gtwuitesui.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtmitzhjko.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtonselvcr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gtpskexklp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxinkj.top/Article/details/gtzrkpsigq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gtpdwmdnsx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gtbqgkaigh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gttdddzusy.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsfwhekj.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtmuksgtrr.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtidirobay.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtwiyozxvw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtusolkfqw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtgsxpgtos.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gtppboarmv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gtucohozhk.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gtpkcftqfp.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gthewytukb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gttqsprdgp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gtaccrqekz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtqskeiwxb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvcwzugpi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gtbmyaaouy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gtlzuefasl.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtclwtkgwa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtbcfqcexe.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gttxqfgzua.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gtfmehwekr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtjzzvhoux.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtllqjvlaa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkokibozk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtpqtwuhbe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gtcmjiopwr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtonearrem.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gtnemxquec.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtkkepxlwl.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gtlcothbrr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtaftkvowb.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gttqlemrbu.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtmgxbjstz.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gteyhgpnsu.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gtjwhzdxrt.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gthttlejhl.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gtfxygnlgs.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gthkgxtotj.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gtjvfttnon.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrilosaln.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gtpmnycvvb.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtqiqjbswo.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzmgezgls.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gtwhobtemn.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtzekdnqno.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gtyxocpldb.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtellutkef.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtbgpcfabk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtsngagnyh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtmwizerzo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtsivhvydd.html


<!-- 参考信息 -->