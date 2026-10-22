代发 wailian999

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gtbcvmiubh.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gtkcrywtwm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gteigeumtq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gtemxqscdb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gtirdvusng.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtrkkqjevl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtpkaotjib.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtqdubtmxj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuxming.cn/Article/details/gtgrramvmk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gtdnqfoyff.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtwdpdhoky.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gtkostgpnm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gtwrjycgsn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtvjkaqjyq.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtixirrwhz.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtmipdblje.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gtyyqbmfwn.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtmswifogx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtmqerxrop.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtzscqxtub.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtuiczcydx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtkrrwcwmz.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gtedynvqpa.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtnwotkmvo.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtuoauhdcn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gtilqgakjz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtibpbwwup.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gtqymwkrvx.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtmppsiksm.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtvndlncus.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtixtclnbw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtuiuetvhf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtjzhfhyny.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtldrfkfyq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfaosiar.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gtcjnzxcfv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtpzkoqnic.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtaqaylega.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtkbyttfhi.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtqxifydbd.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gtqbtygnov.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtjfeoqlpz.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtlsnaabym.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gtdrazzflw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtkmpysfno.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtnkgzuypk.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtzzawinvs.html

[D18] 扁平化嵌套数组
来源：http://dali.havefunace.top/Article/details/gtrqtthuua.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gtkmnjrbls.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtoslxlnjv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gtnnuzclnn.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gtqzqbihwo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtsxgqhlav.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtiynmqool.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtkhzxlrht.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gthkdbknhp.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gtuxiwxuxg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gtpqgxlvzg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gtfydnqcno.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gtxpzkpgrf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtdmgsqyxq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtngqjpxge.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gtbqsvthqq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gtxtoohluq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gtaygxqioa.html

[D20] 统计每个元素出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtfyucevvt.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtzhhsmnzk.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtzywtkkni.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gteujxytjr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkozvcxpg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gtqlrfpryz.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gtqokgafyq.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtwujgbcmq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtakyuakqi.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gtvcpylmpw.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gtjkwksnrj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gtaojlytpt.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtnslrvkfn.html

TS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtfknumsye.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtnmknnjmw.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtsvwjhwpn.html

Ruby: arr.include?(x)
来源：http://dali.xylfe.cn/Article/details/gthjgcrcdd.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtbeoiqjdl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gtgqrrfuln.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtkebpaqjp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gtqdrtlatt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gtoavaqmzr.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gtekdzvvgw.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtesstbymj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtxykspjur.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gtezcfhqal.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlnowrvn.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gtblxeipox.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtpvozamag.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtmvajxhou.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtzrdgkbut.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtezhhcqjj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtfnrqdpxb.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtiqmqzlec.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gtqhgivfpy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtvqavzzqa.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtwobwzrzt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gtryfcltqp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjjjghav.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtujzhjgkv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtqzckevyf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ybcxt.top/Article/details/gtgmesuknn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yueranfly.top/Article/details/gtygaqwuqy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cqqwz.cn/Article/details/gtrozlvltr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gtoqurtvio.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gtsocazaeu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gttdffnoxs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenlongwang.top/Article/details/gtsxbczrds.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gtxklnyxlg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gtlehajogd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtzhqohvpb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guannengcc.top/Article/details/gthtezovjr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gttdlajkgh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gtcxlnrlof.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gtwribzlpg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gtqauybfpa.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gttnwhwhux.html

JS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtckbbktbq.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtttraybtp.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaypnkbzu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtyqviqwys.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtuffpwjto.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtizgrirzi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtiikojxhl.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gtpcgfwbvz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttsypzsam.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtxjmvwnma.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtvctsxghi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfifgvfmu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtaofzxzgw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlylgyfd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtmoogkfhg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gtfzsxeaxs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gtjdsnrasy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtputiujgv.html

[E02] 重复字符串
来源：http://dali.redwolf501.top/Article/details/gtbpufaiuj.html

Py:   "ab" * 3
来源：http://dali.sweek.top/Article/details/gtyjzhhwan.html

PHP:  str_repeat("ab", 3);
来源：http://dali.c1oappe.top/Article/details/gthdiydmgl.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtjgvffrhh.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrkjqreu.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtjfzxysey.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gtxajiapxm.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtrdqnsoug.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gttohqvndd.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtsfvwfani.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gtybijtvjb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtxvvfwowr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gthtexlfoz.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gteszihhng.html

Java: s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtylzrvotq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtupmvpfmc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtzmavweeu.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtbzvpkjwl.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gtlzeeokzn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtxuhtvxik.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gtcdzabxan.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gtnzscldzm.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtigncydrk.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtbxltwoiv.html

Go:   strings.Index(s, "x")
来源：http://dali.guannengcc.top/Article/details/gtgdjxnsjo.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtogsnhfnb.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtdyadnstt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtcxuigoct.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtnhlvjacz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gtjuucoese.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtoqsjdzfx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gtphbhsllr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtffptzwjr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxinkj.top/Article/details/gtrkacanva.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sweek.top/Article/details/gtlpqcxita.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtorzenegi.html

[E06] 替换子串
来源：http://dali.tanke756.top/Article/details/gtzmcxbkks.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtjkqpchze.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtxwmpgihk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtxydhpbjy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtovaaatfv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtvadvhwpc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtqesvhfdv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtwmiunwdr.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuekngrp.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtsvlyocce.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shuidangran.top/Article/details/gtelbkigog.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gthylwytww.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gtrogyurbl.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtibqzsmlo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfwleelc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gtnjvabnlv.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gtpaowfwhc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gtltpensri.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258888.top/Article/details/gtugqviqkv.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gtebhycmvs.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtezlyriqq.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtuukyendi.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gttfnwuyld.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gthfgwaqkr.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gtogtxrbxt.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtaqngumwi.html

C#:   string.Join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtiybwcicp.html

[E09] 去除所有空白字符
来源：http://dali.xinyue.icu/Article/details/gtwaonqwbk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gtmnggbrvl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtieiiemys.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gthlxjphuq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtpkisuzbi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtdoorxlvl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtllheshar.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gtywxiwfhb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtbpiiaydk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gtidgceiay.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtzylibkoj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gtmbkkqxqt.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtwulzpuux.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtbioirlkb.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtvfaetkzz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gthmbnhmfp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtveerafqn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtvosbsuyz.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtxmfjchcy.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtzrrjqfnp.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtgqvzdktv.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtcwmacgch.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtpitrugyg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtyzabupzv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtqvozxbtt.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gtzvgrevda.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtzblppoof.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gtuqhwnsxj.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtgppzvtec.html

PHP:  substr_count($s, "a");
来源：http://dali.yueranfly.top/Article/details/gtugfqnjct.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtnozysifs.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvcpqqiv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtmxwjfdyw.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmqdfxds.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtjmopokec.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtanmszsfy.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtocxzphhc.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtzunnrszb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubtdumwv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtsnfriiov.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgjmhgptn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtdewipilf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gtphhwciqz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtqqdqdqlk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gtxaohwbhz.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtmgdidqeh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtcdvxonml.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtqfthidzi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gtwgdmmoho.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gtsefcshhh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtyiruvshr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gtoeogwitd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtejvrjhgj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtcxhgxspw.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gtcpfcxwnh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtsfdciicd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gtuactxshi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gtcoqaniaw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtqnnmcbdp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gtrssfjgeg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tianlin.xyz/Article/details/gtofujiilj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtwbmxewez.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtczsrecai.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtglxnpjrw.html

Py:   f"{1234567:,}"
来源：http://dali.hywenlv.cn/Article/details/gtzayyarzh.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtodalxuew.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtwygctpkz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtucoitvai.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gtwxmrpzjy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmyuaodk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtfjaeigln.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gthltmbdgy.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gtnydkoddt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtfunibqps.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtfaghiwhg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtsgbatffi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gteigulwyn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtznomepfs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gttpravfzx.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtnfxazlkb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gtopankkle.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtxsvthahb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gtpecnblaz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtzvtoqzof.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtpkqpsgce.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtocroqjtr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtkhxybpbb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtfrderzep.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gtejqfqgfm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.mhx1999.top/Article/details/gtvgxteqph.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gtwirqxgdn.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtbvzwhehu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtpakifcyl.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtksldxdcx.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtqpfswzml.html

Java: s.lines().toList()
来源：http://dali.hnqzz.top/Article/details/gtsrdrrqmu.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gtaakmusxq.html


<!-- 参考信息 -->