代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gtxifidbvw.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtkpoudfyg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtfpghpexk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gtizviuvuw.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gtszolinqm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gthiayptoj.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gthsplhaqc.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtrbswcwof.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtwmxtidiy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gtkyqejkfo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfvvkfnv.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gtaadwfmyt.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gtnewlxvoz.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtsjbtpfrk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gtaqhfmooz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gtwtjrknch.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtgkufwsfv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtmlnhpfdl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gtekrnosjg.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtppxjgtst.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jyoumei.cn/Article/details/gtjkrbqtes.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtydpijuvk.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrypabfb.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtecebqtat.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gtfmbktkfm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gtkrclsxxn.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtmnrmaqsp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtpfekhxcm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gtlqlpbgrl.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gtweqyygcp.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtbrzwrnpt.html

[D18] 扁平化嵌套数组
来源：http://dali.fengsongda.top/Article/details/gtmlyqyqys.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.redwolf501.top/Article/details/gtunkeezoj.html

PHP:  array_merge(...$nested);
来源：http://dali.andypj.xyz/Article/details/gtlddmtmhf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gtqgwjmyuq.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtdxlgedly.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gtsuaauiph.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtlnnjllcp.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gtuufxxpdq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtgdktjtcr.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gthjzhzlgx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.c1oappe.top/Article/details/gtpgapeicc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gtmakqrpjj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gtvtgmjgsy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtidugaqea.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gtmtkehkih.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gttavqjroy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtfdonfuzb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gtkcanuycj.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtbjgezpca.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtionuvigb.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gtaytysmqo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtdwhgxypk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gthhiivunq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtvlzozjts.html

Go:   // 手写 map[T]int
来源：http://dali.quarkkingdee.top/Article/details/gtmxjalxov.html

Ruby: arr.tally
来源：http://dali.tanke756.top/Article/details/gtrutbqrwe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gtanedfimm.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gtiysbwxff.html

Py:   x in arr
来源：http://dali.tianlin.xyz/Article/details/gteflyvdku.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtwwjpwxvc.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gthspsvuly.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnskgirp.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtmveytnah.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxezjrfq.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtckksfpij.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gttimkghvu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gtncohwmst.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gtxdnbuhca.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gtiutzyqfe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gtefexamlv.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gttvypptnl.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtlpgwbjyg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtrhjzgcii.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gtrneuttne.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtatpmpfjl.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gttovtjeso.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtmuxmlcff.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtipghnlsh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtgjyhcndk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtdezdszys.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvheejnnc.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtifurrxhq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gtxyyumccf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gtbsvqrsqb.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gtkabqyesx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gtymahsehz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gtqmbepjfr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gtiokzxzhb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtuwkenmwi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtlgxaamlg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtmohecefl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtyxplzihc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gtccygnbku.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gtwtoyjycq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gtipudtexq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtumlhehex.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xylfe.cn/Article/details/gtgnvnrvxn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveeurnqz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gtvxjwgfer.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gtjurutsbt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gtbaccfbhr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nwbrower.top/Article/details/gtlsrnasik.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gtgncmvvqc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtwaecvyln.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gtixawpbcl.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtlfsbjhli.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtsshjeuex.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtenhipdmw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gtzncvabkc.html

Ruby: arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtrpmruefc.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtbhdruxmf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfwolgigp.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gtgblurkgm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxlqsljwb.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gthjykxvjo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gtsasrlvtk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gtspqtbajf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtbkylanqi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtndftlffc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gtfvngbwde.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtrzjwluoq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gthmnbvuku.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtpjibvkyo.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gtultsdkqg.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtrkvlzemq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gtermjjtsh.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtaihpykqx.html

TS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtoeuhohmg.html

Java: "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtnmzyfidk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gthwpzdqcw.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtfjcbmawz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gtewaykmju.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtkgmxsams.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtfqxdqujt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtnljfzxru.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtunojflur.html

TS:   s.slice(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtvaqyrjvi.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtcguumxfx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gtmwqxohww.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigfzy.top/Article/details/gtnpgihvhk.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtedcuqtlm.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtndnuamsf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtwoknkxwf.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gtxwsslkmo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gtvtgrxmag.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtswzxblki.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtczwvydhu.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtbakcfvzy.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtspcuwgtk.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtunbyviwc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ehwqpu.com/Article/details/gthtgxbtfw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gthcxaxyko.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gtmqtxjssc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtayjbscoi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gtrytyjcus.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gttcqpqovl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtcnsyxcga.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gttkpjyohc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gturhcjwpt.html

[E06] 替换子串
来源：http://dali.hnqzz.top/Article/details/gtxlefmqya.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtumnafhkn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtiyiwueim.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtmkjggdgo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcwyjbxo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtnykvbmey.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtoutrtplu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtmrdxvmns.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtjkfcczsq.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gttnuiramt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gtoftqomfj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gttvvrjuwg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gteqohyfus.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gthgccidol.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gtubickqfv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gtbhelfqbf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gtivjebnxg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtmjuimzdd.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtarlwasdr.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtlqbrpjuh.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtdwllpzro.html

JS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtpacxxsbl.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtvnkbdplo.html

Java: String.join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbucptam.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gtyewwnkou.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtsuzqhrso.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtebyanlek.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gttnmgaipv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gtyygdeyvn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sufxvd.cn/Article/details/gtjtxaqlnn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtojtykkhn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gttsvdwsdx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtztvroybc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtwkfvalvo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtydsntrza.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqtrpdii.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtchnraqbd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtkgoeyqxn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gtbbigkkdl.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtrqjjmosw.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtahigjibc.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtpnfhcota.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtaxsftipk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtwwnixzgw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gtgbjkssmg.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgslnggrg.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtbavltbrm.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtldznzsem.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtnokgsoal.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtyskcbslt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtroljdaom.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtotdtfqul.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtxnnxistk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gthdpxheua.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gtknqtzvgc.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtjgimzkjs.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtbzsbstak.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtvkzuymqb.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtwydmnaso.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gttqbhwcqw.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtxfxgisac.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtpioswrvh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gtomjmxxba.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtvtiialpk.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtxemhmiua.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gthnwopbwp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxyimruh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtlgsghqup.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtlqmfbfft.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gtgtwwjplx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtapwhqddl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtuatlijcg.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrlxqonf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gtbcmjbyga.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtjkeffvja.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxznvrdtg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gtxlctgmgb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gtiaogzezw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gtqtfmxxzj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gtoladbpng.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gtxdfjltop.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gtqrtouoiw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gtssolxkkz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtnbpondvg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpopivtbt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtchkqweyc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gtdfzqvamm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtsuejpeol.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtfosegjgx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtqmdekkrj.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtlrykflah.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtnbnjdnds.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gtfwdgenjc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtrvimrpbe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gthwndwjfg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtwmpigiju.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gtlxboitlv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtzhasfgzw.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gttgedqjyb.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtegccuxta.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtwilgjnjr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtqhnvkwws.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtbblxoptl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtbgijebra.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtllroaxmy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtuwlavqnz.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gtwxjuokub.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gtkrxhponr.html

[E18] 模板占位符替换
来源：http://dali.sufxvd.cn/Article/details/gtgxvemzbp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtbxiofyey.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtvokhdcmk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtamskague.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtfaakfqvk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozqcbujf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtnjsxxgtm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.bjfxy.top/Article/details/gtocwsiiei.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtyveublzj.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtxznniutm.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gtpwxdayre.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtoooundce.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtzidwkvtp.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtjwzdvhfd.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gtpezortmx.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gtcczrwofz.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtzlamtrxa.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gtlizpbnxc.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gtxdeisfop.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gtoxkbixwn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtjhircuqe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fengsongda.top/Article/details/gtxmktayyh.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtimrqvvim.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtkgqgwmsb.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtipjgfpib.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gthrxudawk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtekxrucok.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtsszfspby.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtcyuzihwk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtbgvsprhg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtddphsceu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrwtalrq.html


<!-- 参考信息 -->