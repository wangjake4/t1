代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtkjdpcvwq.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gtnbaxbmvq.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gtpocokzdv.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtrighuihe.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gttrtgyxsq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gtxnrktgye.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtvhyedthe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fengsongda.top/Article/details/gtkbmtwbog.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xziqi.cn/Article/details/gtuzqyugkv.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtscsddwjl.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gtjqzpuvty.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gtqvmqmxpt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtwvunnkrz.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gtpezscjfw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gtszahjcnl.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtyqhfbrre.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtkwdrpubg.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gtvzsmbbmx.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtvvkyvywu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtjmebrcdt.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtumehztga.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gtihjstsfc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtfgaakruu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqclaqag.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtnedbggwh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gtytgryvhi.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gtffdekhoo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gtqfjiegxk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gthyzbetrv.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gtxpjpdsvi.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gtlhfktvdb.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gttjwyigxx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtdiualpky.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtqkshvboj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gtavmsfksn.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gttguuwfba.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gtplzsqhwp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtrryjxrxl.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtvplrokay.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtmbtiqrtc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gtqbuhplsv.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtfzpkecdg.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtmvprtvqc.html

Java: list.contains(x)
来源：http://dali.jianghu66.top/Article/details/gtfmjwyxel.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtatqnkngl.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtgxqokerr.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtvwzqrapx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gtqwjlfdhj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gtucgvnqqz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cashguo.top/Article/details/gtxxamrkfu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtbevbcpsb.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gtzsxtrgmq.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gtxxdfqgpp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtjdkkjbcz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gtdqxaurkk.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtosbotzoi.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtigrdgrke.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gtcottwfhe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtfumlmwro.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtckyvlubd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtuztbmomz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttduxwluz.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtfqfbsmbm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhixingplan.top/Article/details/gtbujndfbl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fengsongda.top/Article/details/gtnubksixg.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gtljsaqrso.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gtvjjoqoge.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtdwgeziml.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtnqcfinxi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtmwetsgjz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtxeejbexq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gtuqmlhmom.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gtusiaxqsy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gtfjerdgzr.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gttdnyxupz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtwjrleoqb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gteqigoizz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflfommya.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtvfiwitdh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtbfcvxapj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gtychyzjly.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtygqmltjr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gtqcljywly.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtjvuxcxeb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtqffzeqed.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtjdecaufa.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtuzpvdgmq.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtgzeyofjh.html

Java: String.join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtfricppxv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtdgydsdhs.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtuvxiebbd.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtnjudlfxg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtualavwcf.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gtydoiswos.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttxsnunuj.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtrovxjhpu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gtbsiskaxt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gttxsjyqyh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtwpoqwgyd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtlzkzcinv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gtpuouofyh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkgwgwup.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gthhgobgdt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtfybbuauq.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gtndfvyaxi.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtlhtqemtu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gtfdukurdc.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtqizgegqh.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtqrpimbwy.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gttnczejye.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gthgjwahgc.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtzpaukqpn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtlyplvcwp.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtuftfzpza.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gtxrivrktc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtmfrvrxhl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtrvknoyxp.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gtterxnbpm.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtqgdcnwwm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtcvkoccyz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gtuedipxqy.html

C#:   s.Substring(1, 3)
来源：http://dali.mhx1999.top/Article/details/gtcpievqcs.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gtpvzvjcjt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gtjzbqfhqs.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gtgwxkbesm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuanzhike.top/Article/details/gtvombzmoq.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtvrsoxkhz.html

Java: s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gturkinogs.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtrwrpqmfj.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzirhiwd.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakmlaife.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtmmpyjpgq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtayvgkltf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shangyingyoupin.top/Article/details/gtpjnddgir.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtvgcbvypg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gtdcuoouim.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtaapdwpnb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gtylzmandg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.havefunace.top/Article/details/gthhqubxqo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtzcpfvhhn.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gtwxpxclpw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtacnyjgnp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtxrpycykd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtepxvwvha.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtjjgeckbg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtkibrtyia.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwlaljqn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtbvyuderx.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtipcrzkye.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gtnrommhuz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gtkohjhche.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtohdriiil.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gtyvrvpmjv.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtyqtqflgt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cheryme.top/Article/details/gtbebopqbf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gthlpsnsdd.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gtyzcwhrue.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gtgpfbvtdl.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtepjepxta.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gthhaeqgwp.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gtwozyzmku.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtnibaoooy.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtvfdiqrny.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtjsrprndl.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gttldbrulw.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtthukqwui.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtbxsyriuy.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gtbnxjsytr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtcqeirtev.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdrxgmrn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtqcrsoeyr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtmizojzxj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtczpscfta.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gtovppdqnz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtpabmwhbs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtjgjrtdsg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjritwtgg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtmiubkrev.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvnllnqz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtjheevvbw.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gttogogcxf.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtpiogjojy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtxoibgvkv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtizrzkvwh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtfwlppvsj.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gtwmnvyoco.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gtgvvdimpx.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtmwgiuohl.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtsefesppy.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtorokskvf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzahorvzo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gtkqxoqzfu.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtfbtlenly.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtdlzyiscq.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtjauvktbk.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtehiaohfr.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gtahlwqhqr.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtmarvfjda.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtlvohfkwc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gtinenuzvw.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfbvhsch.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtzzretwci.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrveyiwn.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gtarphbpiq.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gthhysnslf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gtudujshix.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtgfnomjcl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtjpukrmgb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtarjndvfl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gtbubjobyz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gtzhjrvfcg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtfzcbmdsk.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gtaafyaxhl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gthdnknezr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gtgnmiwazd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtnsfnltia.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtaofofyar.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.andypj.xyz/Article/details/gtwnbdzkik.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gtbluhpmns.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtujjehadd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtkfwzandt.html

[E15] HTML 转义 / 反转义
来源：http://dali.dashuyun.cn/Article/details/gtrzhnygbk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtuqquekum.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gtnwfarekw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtjaiozdmf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gtvcowgsik.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gtgujthsme.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtmkrhofep.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtlqbnuxmg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gtydxljpvu.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtagqocucp.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gtjpfuulwy.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtxqdmtzsh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtntnghzfc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtiqjnkcpf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtqqlsoutd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gtnhicgbok.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gtufnmpxfe.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gtzqwaugwa.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gtokleolbw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtlakmnrcw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxsixsna.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtausklqwy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtsbxflaow.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtdiqvtcrl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtyvthlxuf.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtkuxyzrzc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gtwykftjtk.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gtzjmawcju.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtlujucjam.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzggbyjlu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtobpatpsv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtopeaqeqg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtwyplethn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gtljowfqfs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtauwpnbaf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtkadefhnm.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtwadvatbu.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtlkvjpydb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtaayxenbm.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtophuzxuk.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtdsdamouf.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gtcukxmeuz.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtzhigvhge.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gtviimesnt.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gtuyawstlx.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtnoviwgnf.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtnnhvvhqd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gtvazbwiqk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtimhhcetc.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmavhnvx.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtfsxcrbym.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtqlvtkhxx.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtqaivovxe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfdkxqpsg.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gtykzedikt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gtzdcgguyr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtrnievxum.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtvdatfsqa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprizkqua.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtfayzjdas.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtbkytqfee.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gthvvcqxqs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtivchmdqo.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtvrimjkro.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtthphqvgg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtbrtllmti.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gticefobwx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtoyktzfmb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsdcgmny.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtvfeeicxj.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtusedindk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtwmyrvzeq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlnaxpgfz.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiuyxtdc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnhmlfkul.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtypzxxsut.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtomtoinxu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gttxmpmtau.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtghvepnuy.html


<!-- 参考信息 -->