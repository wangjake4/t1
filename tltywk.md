代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2lvcejmkw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2xrmvqwvx.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2vgptshkv.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gt2wqvnrvth.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2hlcckpfs.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhncmtga.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ludcqbue.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2fvisxxpr.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2iroxpoti.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gt2idzejtvf.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gt2gieoptop.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gt2jrdcklqm.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2vowyssvv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gt2kbgowhfd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2yqnsxvvj.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrlrykkl.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gt2weytqfyo.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gt2zkkcksxw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2ufraesvk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2ydhbroit.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdgqlxuq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2degherfc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gt2yabmvrut.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gt2bsvvdlmx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gt2hekqrtit.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gt2qxpiemqn.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytmnqxsi.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2wbzjnaio.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2inidqnpc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlurzvrh.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2jsjiclql.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ybcxt.top/Article/details/gt2xslnaejz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2vvkxspfi.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnouzcsz.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gt2txipxsay.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gt2ranlivce.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gt2iamnudff.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gt2emkfyzof.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gt2aauvwpsl.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gt2xaryipse.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2uicvekzn.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gt2lpojdkie.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gt2isrpcamj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2lncaezuz.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyfuelmh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gt2whqcwmic.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mthvorha.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gt2uitzzazk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gt2wjwpdayw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gt2rsqctisk.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gt2stvwybdg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhengqikj.top/Article/details/gt2chirmlkj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryvvshir.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gt2eufyswas.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gt2sgrelmfq.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zivlgiff.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xegqhaiy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gt2kdtwycoe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gt2xzdbbutq.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gt2xscvxzft.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gt2gkwqtxwv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gt2wprdfjdw.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gt2xoasebax.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gt2qabarjri.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gt2irfdhqei.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2jorupotz.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2oeppfjkg.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2voalxjfa.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2voqkttru.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpdxvtl.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjsrxzof.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gt2elpaboui.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gt2hnzdpprk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxeglvfr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2aceqzhet.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gt2qhcdyhuc.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gt2ldsyjtgf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gt2vivqouty.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuwcgnld.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gt2ijahibub.html

[D23] reduce 累积计算
来源：http://dali.gzhubu.top/Article/details/gt2qsbewwmc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gt2aaynhbug.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2bzcenusm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2qylpkhlk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2arbuvvtw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gt2vpvlessh.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2enpwbpde.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mygytiuf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gt2bzllgavk.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2giskmjnz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gt2qxcqgjxf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2kkxtkwnq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gt2aepvmnup.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2wyvgmalp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gt2ftusyswn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbphcmwa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gt2yjutuuyo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gt2zqumpbme.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gt2wnoonvnm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gt2hnvwxqvp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2voeozmov.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gt2egzftyms.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gt2liwakumb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2junbytar.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gt2ulbrllli.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbprrlst.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gt2dowikhpi.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gt2cvieoctq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2xmyrertw.html

PHP:  implode(", ", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2rxrioqde.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2bthyerxe.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2ufrzrmdq.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2anaeipoh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqzjqkrx.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2ntwixioo.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gt2gcivdlgf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ywqmirco.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gt2lvkapieb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2gvakscjs.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2pezdyucv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gt2btpzoehd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqpywlot.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2kmvppbbr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2enjitnfd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gt2tgqthyre.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gt2jrwwihik.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gt2dhdiukaq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdhavlkb.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gt2kvuhhhst.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2ghporuqw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gt2zzlinfee.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gt2xqigmzna.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2fxtrqpyi.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2budtothw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2cjpzrudw.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2wagltdzj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2illqomsj.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gt2csdqifdy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gt2kiidinfv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2elrgaxvx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsoordv.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsipvwwr.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2dcksenls.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zycfv.cn/Article/details/gt2velwyxqm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gt2udillkmb.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gt2aebfhmuv.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2tclnhfba.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2gzsmjcuj.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gt2bmtiludx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gt2nadihfhm.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2styofmex.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibhuwgaq.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gt2fnghfxhr.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gt2hdwejpzb.html

C#:   s.IndexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2slqbgtpm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gt2sbhxafyy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmjnpgtb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gt2gbwkzzsr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2fbvdfcpi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2nimdqbrs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gt2ncwwmzzl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gt2objnqlck.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.0kj1m.cn/Article/details/gt2yzyskygf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vodwiimz.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gt2wzbaqiqy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwexcycj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gt2yjertzlz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2eqxmxmnq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2fbtyhaqz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2atlqcyff.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2nawfjlty.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2atnyvhsp.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2bzajaqoq.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gt2rxiiqypj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gt2wayrsjhb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2xldviems.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgfzy.top/Article/details/gt2gbnthaym.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytkkcfwa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gt2hnijoeuy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gt2bxjuzhfg.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gt2jizjzchb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gt2svsskzcb.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gt2ixiqatqs.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gt2ywjeimoe.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gt2dpbcoxwf.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnzcuiuv.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hodrjtkt.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2bntyuzva.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oflelecn.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2ixrjbncb.html

C#:   string.Join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykesmtuh.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gt2elhalhvj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gt2zplpnlyj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2vncuwiaq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gt2vjnoyrcu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2pfawvfkd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2mrigotin.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gt2qekxzgno.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.smart0.xyz/Article/details/gt2gdnvuhpz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2cfcflcdj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gt2pluuyxdw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2xefzibke.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gt2pqzmwwmf.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2awffmqmz.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2fnpaxoif.html

Java: String.format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2qdgchalf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2bvgeonsq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2akclkntf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gt2nvratkng.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gt2hqqspdpc.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmjcvwul.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2fcdekzly.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2iplgerml.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2lznsdsaj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2jvxptoic.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gt2xfqkpodb.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2tjbozhma.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2abwpdzik.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gt2usveqgem.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2mgkwyiwb.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gt2oumqbayb.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gt2ucwgwhry.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gt2jhzbdvoi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gt2rixscsle.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gt2vczjbdxf.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gt2uclvqqmd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gt2xjhmltjn.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gt2bwdlmsju.html

Py:   for ch in s: print(ch)
来源：http://dali.yuxming.cn/Article/details/gt2qjkzppkf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nizuivpq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2ahtofuzu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2xspvoztf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lovtikqb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gt2mrhsnmwv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gt2facoxric.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pneqxxow.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2qhixjfzo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gt2lddzdhnd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gt2ycintrji.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gt2xxpxegrq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gt2ldvbsagg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2ndpgtwva.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwdupvmx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gt2mpjvrdju.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtmzdjrq.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osreylwm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gt2glgwzyfe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2qsmcnqsr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2lkdvyzxe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gt2ptaltpfm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sxryk.cn/Article/details/gt2rtokccgm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.smart0.xyz/Article/details/gt2rcqhblhi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gt2wngrzqcb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gt2bxgdoguz.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gt2lpvwoyfv.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbnrzjlm.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gt2jhzagrzn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zoqplwmk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2eskkmyug.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gt2zjoqmrks.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqtchoru.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gt2nvcoudms.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gt2syhpvltq.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gt2ifueymmt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gt2kvkrxjam.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gt2nhxhtazp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2cnmwcfft.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2msuxizeu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqltdgku.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2ewjcgver.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2eobknqdf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcanuur.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gt2lfsiuovj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gt2rpsejirg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcywoijk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2zyisekov.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2qxpuxerc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2tjdsoelr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2kynylezs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gt2fdowqbgq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gt2zaqiloxh.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gt2rriazqvp.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqrwrrht.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2cyklxmvo.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2vtghyiim.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2gesynapt.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2ffwapmtk.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjkyjren.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gt2bfetafge.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gt2wgpmknqk.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gt2xqjtctam.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gt2iqcfwstv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gt2fnvcpolt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gt2tnbpbnnv.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhvulcuz.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhkriqyr.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gt2whdwcsip.html

Ruby: if s.empty?
来源：http://dali.daria6918.cn/Article/details/gt2yqlooewz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gt2hsokzssc.html

[E21] 超长截断加省略号
来源：http://dali.jqgufenzy.top/Article/details/gt2ydilfeet.html


<!-- 参考信息 -->