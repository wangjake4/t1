代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dianchejie.cn/Article/details/gtrxuulcmz.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gthbpuvwjr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzbtjzxi.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtykvwurij.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gtndlqbvzi.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gthbhmmrep.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtwqdjtovd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtymsyjval.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gtlpcitktu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtwlyrmjvl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gtjwlqnqjh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtvazqeyfq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtdcqeulfr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gtbzikclqr.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gtbijbswza.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gtntzlswim.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtztqdxgen.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gtulziekbb.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gttseyxqxe.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gthqhrxfug.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtxcfwxzxu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gtvbqhjdzi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtmkbjpkdf.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gtajdeqhhh.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtcbgqjekq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gtghiuhpmf.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gtnxfndryx.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtfxwkxqxf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gtmdjzykin.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtweowzymf.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtczbynmwu.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtdjjcznog.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtdhpmgpuy.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gtncpaosnf.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtqcqxwmxv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtbeiphcyt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtimupwbpo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtuptdnmpo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtfxuxmzsh.html

TS:   [...arr];
来源：http://dali.feifeiyinyue.top/Article/details/gtnmvqiizo.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtdvugphvz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gtfblxenjr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuetiantiany.cn/Article/details/gtysdcmmey.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gtqjefdnvp.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gtamyuevfu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gtshknyjxn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtthufbyjm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtgkggquon.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtxpimvvfw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shangyingyoupin.top/Article/details/gtnoojoara.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtqyomngcp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguhsvojd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gtyjiveddv.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgvvzrrq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gtsxlgpamo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtxyxqgisl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtadvwuejv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtpkcqrfdb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtgkwcytgr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gtxkjamtei.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gtopdeimcy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtvjgjuvbu.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gthqtngurp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gtnuzacqci.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtaitgfauz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtueofcekq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gtkrooyncy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gttafxnzkq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gtfnryefvo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtevtqzupu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gttutrcfyo.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gtcmazyach.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gtrkysgszi.html

PHP:  implode(", ", $arr);
来源：http://dali.pycfn.com/Article/details/gtsvkwacqw.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtwocscqst.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtkwafmpuv.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtiwsqgbzc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtxttjinbj.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtxgynrmob.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gthnujkflz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtubxwtrwb.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtesyromjh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtboymfent.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtkclemlat.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gttkvybjux.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtqqcruddm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtgbleiord.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtjvepvrme.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtjsxlpyjz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtrjwbiltl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gtdgsyfwnq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtvsuqnzmy.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtmvxgahdd.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtkrirysaa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gtsbfpwlku.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gthsmvvofz.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtgroxxujz.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtkmzrkvap.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gtrucgzdkp.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtxxdrttgu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtjjiygtdy.html

[E03] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoyhwelm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gtrxdwrjkh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtnvmivwiy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtcjutyhmy.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtxomsxlhb.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtrhiuqvlp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gtityvjkfi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gtolzctvpo.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gtplnlbefz.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtetzsjfiu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtgexjqahi.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gtryrsbhic.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gtswtcqnkr.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtahpxynqi.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtxpvvzsau.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gttcepcsyw.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gthwiqdlij.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtpyufllmm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gtfrqgfhfj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gtdctcdeow.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gtlyivfvbg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtbbjopjfv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gthdtbsxkk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzzqcprt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gtghlgqhkh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gtjzelcgsp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtifzzykpj.html

[E06] 替换子串
来源：http://dali.xuanzx.com/Article/details/gtuccpozkx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtkumylfkv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gtcjasuzcl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtzovfmrtl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtywuwqdeb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtckyjnynx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtirxamnks.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gthzjqmyvt.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gttyullklb.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gtfbydpsfn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gthfttpqnp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtyokbyatx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gteqfepmab.html

TS:   s.split(",")
来源：http://dali.xuetiantiany.cn/Article/details/gttdicqjhs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gtjrlkkeny.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gtmefwbsau.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtndasjdja.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gtajxzpquc.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gtfpghkdnd.html

Py:   ",".join(items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeabnxmm.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gtmopqptpi.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtlywhiqdz.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gthpkhmyim.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtxsochodv.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gtnpzamyee.html

Ruby: items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtbzgsjdpx.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gtvqrdjunx.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gthpqufgdj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtgffdnfcf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtkastqnsf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtyzpuucjs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtfoiaiqlk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gteuwhaatl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gtdpvzjhcz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtdbhwmybx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtdazkbnsa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtktpnbpwc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pycfn.com/Article/details/gtpcopaaqp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtdjdntbyn.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtbunqmcpq.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtvxmuyjek.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtioyxctpx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtkjxwjbpx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtpdjnsxvt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtvpkaeyvi.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gtawqxvbav.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtgbffcsmm.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtauglzopf.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtualcrlvg.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtopqxaswx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtqtjnzxkg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtyyoxlmdk.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtrrbzzppl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtiojyyoqf.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gtybnudbhf.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gtmqafvctp.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gtbzmmlrfn.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdacgppb.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtfbouyhbi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gthtfohreb.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gtdkghovjo.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gtbmhluenb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gthuedwbgb.html

[E13] 逐字符遍历
来源：http://dali.yonumen.top/Article/details/gtnssrttwh.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtuhyqbprt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtvracvgqz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtrhbhgxgs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtzfnvkfqb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtjopzuxsn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtviowcipc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gtykzkwsua.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gthnykhxqq.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gtajzhlrom.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gtnkxjbmuu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtqokadsey.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gtklncxofv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtylbgycyh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtfxtsnree.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gttxrnecvj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgdgjxcc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtmoxverok.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gtzgamaksk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtbnwvxqjl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtpuxalhta.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtxvzzkemy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgbjsopq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gtkojrjyko.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gtlfgwbflo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gtbqfticnw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtvgolpvdr.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtfrfchnng.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gtujankfjg.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtgkxjowzr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtgqrqpmwr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gthdssqwfx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtvzaxqekx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtdkxphnqg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gtgpdftrkf.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gtrsbflgxf.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gttbzcgtrd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gtfefnakuw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtdndgbnlc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtghalrnno.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtqzgcdntl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtmxgpvian.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtcclloday.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtdcrqehoc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtkbymqhre.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtngjfrzho.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxuanxn.top/Article/details/gtgnbwxkre.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gteqvhsmni.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtpodkmjlw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtegqrkuci.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtpqnxmoid.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtwsaerkio.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gtchrxynrd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtockwloxj.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gtqmvwiehb.html

Py:   s.splitlines()
来源：http://dali.yj20258.top/Article/details/gtzjdabmfb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtyclfbvrz.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtlejyeedm.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtfwuaznhd.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gtrqleusdl.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtvwwtqiaz.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtpmwacibo.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlmiatrh.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gtyytcszer.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtdiiubllh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gtbwhpslsu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtavsctkmj.html

TS:   if (s === "") {}
来源：http://dali.ehwqpu.com/Article/details/gtiitwabho.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtdqodlksj.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gtgyeuuurh.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gtdikerxfc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gtwzokvgio.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtsedfogpx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfoqkmwa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtvtdiecmj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtalkbrkfa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtapzitibh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtyupdhtqp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtrstpdomp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtewnyvytd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtyjjavtwp.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtqfrarurz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gtquvxzedm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtdqihfqht.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtancsrfbb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtkpphcsrd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gtpbrxwnid.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtpvohumvy.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gteodnzanp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtmtsygimc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpmrkgpvr.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtmusuttav.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtopcjrobo.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtrhaqubkx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gthbpkoeka.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtsnnjbdkd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gtcuonongg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtqhmbqdsm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtulozeroc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gtjiudeqbh.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtlxovhivj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtttnddqht.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtsjkatmae.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkngxvmkq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtdjkpvjbv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtlbvfvris.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gthmtqghmf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtuhysrlva.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtydggqjjh.html


<!-- 参考信息 -->