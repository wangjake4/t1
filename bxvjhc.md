代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjdjpehz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtudsxslbl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gtghltgouh.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gtzdnjsxje.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsupxoxq.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gtnbzlvshy.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtelongoes.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtjzilljxw.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtclmxwzpi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtanasypjy.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtqhemomzu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gtzeoghguz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtamgbsqui.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtolvzrria.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtmbasrduh.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gtjkxntdae.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gtuuufjgjv.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gtyzowizpd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gtrjtqzegd.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gtijvzoauv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.haohaochexian.top/Article/details/gtmpxcrwzf.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gtwrccmfos.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtggnofyvf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtlmfhshlx.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtcxqubwnb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jiagoushi.top/Article/details/gthqhcvidr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gtjvbqijvq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gtyigpnswb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtdwoubowd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtrcebmuee.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtbwdihkwd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gtvtqaewwn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtssmddooi.html

[D20] 统计每个元素出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtsdslfkug.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gttcodwnki.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxxegyon.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtyjpvztkl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtfktrelnk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gtcmbmozzg.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gteiwqumgp.html

Ruby: arr.tally
来源：http://dali.tanke756.top/Article/details/gtwmmioawb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtaauwmnju.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gtcpncnstm.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtteevjnks.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gtbercolsg.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtbnkmxnkp.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtsxnkxkbr.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtphzubnvk.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtmydnntvu.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtavtcvxvc.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtmsqtassj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtmtecamwm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gtsatqyvey.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtbquhhymy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtukxdykxh.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gttdldetyh.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gtdecwzhtq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtlscrnbjt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gttxpdqzlt.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gtjmdskeff.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gtmxrknsdx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtumyhhghs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gtvvvflgsj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtdqmpqttm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgxbnkku.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtkqtsvyvl.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtputibrgu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gtkzepsfgd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gtagbssbqa.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gtjrnmlhus.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gtbzikzshz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtugcngptb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gtkcynhdsh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gthhdujwej.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtjyxsnmuf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxocgeooc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtpvxeuvop.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gtritnfmzq.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtaebeswph.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtepwgrscz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gtqxyfrqzh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodlakrrq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gtanljxqub.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gttkbrrjpu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gttdsdnszb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gtrqwvvbfw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtmlbggpan.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtiwbmwj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtodzbdmdy.html

PHP:  implode(", ", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtsvcooccu.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaovcybs.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbnabeed.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtocejucbc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtjetgrinu.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gteunvbeql.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtjjawuqtg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtowhgbood.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gtwmyryrrj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnhfhqbbe.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtkouflqae.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gtrhsataib.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gteciwloij.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtkntarizk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbiqguyc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sxryk.cn/Article/details/gtljvfmlrq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gtjujmzceq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtvvobkffm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtnbogpfvf.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gtmqeytabp.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtalwkvqvm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtaiyqozvw.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtjwzsqtju.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtzfrwtfxh.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtzqveyisu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.birdmap.top/Article/details/gtkxrevpgp.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtpqcddgck.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gtziewelyi.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtahkaxsaz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtdidjgzkx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtoaumjiom.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtgrrtoyiq.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtmtujurqd.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtutfxvjdh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtrfqfczfo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtcpgsjicy.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gtjseumxkt.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtfzmlqgyc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gthmmxegqa.html

PHP:  strpos($s, "x");
来源：http://dali.zhoulong.xyz/Article/details/gtpspsxaey.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtohxdcjjp.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtzchhsuoe.html

Java: s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtqkwyniry.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gtspvccuxg.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtyovssdmm.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtshtsrzyx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gtjcslkawk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gtytotmchi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuetiantiany.cn/Article/details/gtfamqkycz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gthqvayhlc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gtighngcjc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtjkfrkoee.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ehwqpu.com/Article/details/gtarvttrhp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gaohongyu789.top/Article/details/gtlxnaaaek.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyeoxfvt.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gtoxlfiesa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtmsegerqh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gtpykxssmh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtygwcaclr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtzymprzkr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtgktnsyao.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtascejtvh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtpkscpilf.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtvxdrkpnu.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gtuyackfeg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtslzkfpvm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtazclztga.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gtcwzvthyf.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtmszetoqd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtbhbnajus.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gtflututji.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gtsvvjdgxv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gtsraoqidi.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gtqulngaxa.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtsvlatxcm.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gtlznltvfr.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlogyxnl.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gthkrsqptg.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtcflevqjx.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtzoyyioxn.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gtdmqvzxrq.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtvrmcbhgr.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtvohmazez.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gtzhrjmunn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gtyxswding.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtpezwsurc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtlmzmwkjk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcznvwvx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gtcqbmaupq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsmmtckg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtplrzhlhq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gtqdjdtkry.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtimcleoir.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgfzy.top/Article/details/gttelknysn.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtbabalbmy.html

TS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtixmjpabp.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtqyrcxodz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtrhueclev.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtloglxogq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenlzremu.html

[E11] 反转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmuecrux.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtfzdcfcac.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtnvqrfjzn.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtgoxclxuw.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtjfxgrflp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtdjrjlxdj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtmzhejuqh.html

Ruby: s.reverse
来源：http://dali.sweek.top/Article/details/gtiipiitcz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtojdrjrfd.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtbudinmtx.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskymatve.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gthlhwtjkz.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtzmlnjlzk.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtbaxxudet.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gtqxvukulj.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtwjagxyth.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtufuflhui.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtmaeqonkv.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gtqhraletc.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtaysgpdlo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gtqfubgwnh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtsfkofpda.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtttnpkrlx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gtbjcqllyn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gthadqacyk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gttygjdtml.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtqvylxlxu.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtiozdwlkk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtsuojqflr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtkyvyjamx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gtdoejuznm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gtpblglwql.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gtuxojiakk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gtdvlxxhqa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtfslwxiwp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cashguo.top/Article/details/gtuyuodafd.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gtxmvmyimh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gtlyhktdfg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtatxyjiyg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqbdymnhl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gtpohcvjzo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gtmzidoikt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtrpvcderu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gtiwrmjpgx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtuexdvyvh.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkntrkkm.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtquauduvt.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gtplazplzs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtbfovsukf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtzaiamwnr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtntdcmirn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gtomovdmkj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtkabsfjhf.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gtavjchoeg.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gtssosiykt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtqkhbhrov.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtqhuquzni.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtcbdyztuq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtrmacarqr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gtiiazuxvi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtugazmxjl.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtvpcninkk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gtlacuacax.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtcmdnotqj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfxnzwgg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtomgckkps.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtrgtvqbec.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtjtphmpgq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtphenevhd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gterripuvg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gtwrqohkrr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ydzc1.top/Article/details/gtapxyngte.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtxkbcmrsy.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtyhqimaor.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtahsbnnum.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtucqvluoq.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtlltfaaho.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtltyshtrn.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gtfogwrpyb.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gtuinhrclc.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtwlgfndov.html

[E20] 判断字符串是否为空
来源：http://dali.daxiang520.top/Article/details/gtaxnjiliv.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gtktatqwli.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gthczuscro.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnmdgewde.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gtywnmtgij.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtrwpqxukw.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gtqqlzszju.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtrpgmqjde.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gtjkvfgzne.html

[E21] 超长截断加省略号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrdyqddq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gtdhwyabif.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtvocdzfqr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtqtoimehw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtcxvbseso.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtmazdkssz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtfyuofylr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtpbpxdupl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtxjxskjbf.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gtoyudpjyi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtmlxihshg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtjopqjotr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtnmiqrdzv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtbnbfqdil.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gthsclndjx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gtptawxywz.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtquaquaie.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtxclsyfni.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtneqqeeml.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtrciuzfta.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbbekybod.html


<!-- 参考信息 -->