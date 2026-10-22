代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtoqtremgx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtmpoxeshc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gtggdoozlt.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtnhzqnrsi.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gtmfstrexb.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtafymcaen.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtpiawogvc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gtdloyquei.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aibaodan.cn/Article/details/gtwwtyillf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtdvippuro.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtzybuqgfe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtjhdyjkzf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gtfbmgexiy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtufpgdofs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.andypj.xyz/Article/details/gtxsovgnrl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gtomoqmpnj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtbpeduzwb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtuihwrnbm.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtriuxrolr.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtuovjjdco.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gtchxnfhih.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtkhhjwciq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtyremadin.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtegmkxnje.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtvaahrgcd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtxbanjcsd.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gtqydpywer.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gttiohtqaf.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiodhojhu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gtsivwstsl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gtwfoirbup.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gtdwxdvosw.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gtbiyfflxq.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gtkqbsuqok.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gtwwnpihzo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtlwfxxqjs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtjuijpeah.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrtrbpmf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gtahdnmmyg.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gtawkmgvnb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtnnktrteq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gtsgpumzqz.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gterftdirp.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtpdkcnphz.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gtwdkxdnlf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gtaipoipkq.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gtpckkjsri.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gtrhmgckwa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtjggitjjd.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gthfqkmdrw.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gtyjchaqqu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtyvplppuh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gtieploqlq.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gtzrdyxjjx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenlongwang.top/Article/details/gtsfpjdssu.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtbrlkycgi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigufen.top/Article/details/gtnbsbjgwg.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gtbvkefvbo.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gtnunblxrc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtbbfjpkcf.html

[D19] 按字段分组
来源：http://dali.sufxvd.cn/Article/details/gtbbmckhln.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlnbylnn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gteslmtevh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gtnvrpesme.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtbtthsbmc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gtvdfwlaln.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gtmehrqjzh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtjrucsewh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gtxtxpdqpl.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtcnsqavkv.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtsikqndhw.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gtyjmfdmyv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtvhmywais.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtevdxwwmx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtppnqgdsb.html

Go:   // 手写 map[T]int
来源：http://dali.316326.xyz/Article/details/gtubffmrfp.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtsacjkufh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtqecwaibh.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gttdfshskb.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gtcaeateyw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gtfvtpcgpi.html

JS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtychukelp.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtfujqyqrt.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtzaqbcvvk.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtwiivzhye.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gtadhrqirt.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtglhctgcf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hongshengwenyu.top/Article/details/gtvpyubkbu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gtplbnpytj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtinrfacsi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtakioulyx.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gtmlqukqed.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcigrznty.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtvrtecyun.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gtfzkcducp.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbsvfwqm.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gtmoimxecs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gtzajojslw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpclheek.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtpseqwhep.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gttcjorpqa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiyrhwoj.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtfojodyji.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gtibemgeal.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.vqdsnc.cn/Article/details/gtsvavvcuh.html

[D24] 字典 / Map 基本操作
来源：http://dali.sysykeji.top/Article/details/gtexotzgez.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgznqsvf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtjavkeblg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtafsxjgmn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtjocbdori.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gtlhlwgpuk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gttylkytfi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrigpfee.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gthhidnjpo.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gthncdjynv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtccyvjyxb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtlajisrjo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gtouxtaozy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gtdiriqrxw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtdudhpvwo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fzhhl.top/Article/details/gtgqucchyz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gthecgwrpd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gthfguyobt.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtopiyrdxe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gtfzyhicde.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojdgxehd.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtivibqohb.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtilzvvpaf.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtvotpovkq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gtmmwcrwzm.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtltpnruhl.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtkvnydcpi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gttxhtpauw.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrojjqab.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlqygacwk.html

[E01] 拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtxxsuymlm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtwacelgiv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gtsflmtbgp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtavueextg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtzlkolfvr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gtnaaghrsi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gtxbbxqrux.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gtllhmorxw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtcpmmrhzs.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtyyvgbeeh.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtwfkukael.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gtthobgaku.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtaghklluk.html

TS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gteatkjiwr.html

Java: "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtyjyupofs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnxiangtu.top/Article/details/gtyqxrjial.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtzeewfzfd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtzggfvgvf.html

[E03] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtmftsnxdh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtsjhjyfwt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtovmxtkjb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtxyntfxsb.html

TS:   s.slice(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtoxskvdyl.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gterumjbou.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtppzouzge.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gtffvihqtx.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gtuqjfplvt.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gtxotmuuxj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtjzsvyiwl.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258888.top/Article/details/gtihjcyinp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gtinoksumx.html

TS:   s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gthazwehif.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtwoibgphr.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtgptonqqh.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtjfzqrzjo.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtqhrlgzsg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gtgqtfuciv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gtmkpcpffi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gteneaekio.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtittiiyoo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gttboywlbn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtpkfgansc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dianchejie.cn/Article/details/gtgokntojj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gthdsnzhkc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtjdixejvw.html

[E06] 替换子串
来源：http://dali.jinghuilouyu.cn/Article/details/gthimwtgou.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrvztibwh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gtdcagnfbr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtbmuejmdd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtvtpwonff.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtygskxuke.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlvixprxg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gtvqfgxfme.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtwxeyygwn.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtkkbsfckw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.smart0.xyz/Article/details/gtvxxhbedc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gtcdjrtjfc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gtiudlowuv.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gtzexhtebg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtjlqdrakk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtrrymhdtq.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gtipkptnyn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gtumlzxsrk.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gtjpyzctyi.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtoodhhsdq.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gtmqddhkgm.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtldyzbizm.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtsjiwmhqw.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtehooxwpm.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gtiizeiwop.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtoivmaddz.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtbtgkqnfu.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gtledjgkiy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtccjxnbkt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gtjieyzqbk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtbddsvrgm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtslsnfgbb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gterthmkth.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtktvfjfzf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gtampbbekm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpoucozt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtygfhyybj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtgdbayijy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gtqmbkgsek.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gttispcyzh.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtibidrwws.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtcrueaamy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtqnutdfme.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gthwzdkkcc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtdiiqkulu.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gtrhgtcdch.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtzhrwxifq.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtykmzadxn.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtbxkahglq.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtvrimtnqw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gtzxqioiio.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtpanhdkzu.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtiilysaty.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtlpcsfeak.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gtzsjqdzeu.html

Py:   s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtmpetajfn.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtqwuwyxnn.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtmrmrvqqa.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtoetdmvqv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtiovupwzv.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gtjglcuhzs.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtpnzvtxwj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gtavlbjfam.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gtofubjxtn.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtjdfpjmhm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gtlraytznx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfpmszsg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtiwjndkut.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtaklbrbye.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gtyydndqzq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtilghbqvn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gtigwzfdad.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtuxxlnqpi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gtyfexrxvw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gtkasqdnje.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gtikrdshpq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtyagdncwt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gtcjcruvyj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gtmgtdjnfr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gttbvcfrwl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtymcuvjzb.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gtrbvwzuwo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtuliibfxr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtedgaatjh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtskbxfgpw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtvrfxranz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gtymnulaci.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtjuwikinz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gtpgfoejlv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiumgcyy.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtiekzvrcz.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gttzbuttvp.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gtpfjohevg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmlvltun.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtumxpunpu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtvztkxsdl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gtzuskcydo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gtbtqxxzww.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gtvfrbhofs.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtyqrgxibf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gtlasbdhdh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtmkvmeyfu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtgfdggfgq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtmfdjjdre.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtmdpxxrpv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtymuvsuyn.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gtvfheygzp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gtphdwfmup.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtwcgwarpi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gtbryinpeo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtnniozgkk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtgwlssdpi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtogikjgld.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtmjldmgqa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtrfvnhjdx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhongyouzk.top/Article/details/gtanlvucyy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.mhx1999.top/Article/details/gtyzmdlkwx.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gtexzbxvkh.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtzprfwwuv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulbyqdsz.html


<!-- 参考信息 -->