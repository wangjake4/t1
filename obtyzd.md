代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtolyvxsfj.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtznoyusnk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtdoavfsnp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtihininet.html

[D15] 去重
来源：http://dali.chenlongwang.top/Article/details/gtryfyalew.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtmrirfkin.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzuxrkmh.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtgchafaap.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtptmupacg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gtbddfednz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gtncupymus.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gtrdmjlolg.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gtbcdcamhd.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtklbiogpf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gtjzlapoyb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtsvyoqrnk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gttrmdkjsi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtlqqjlpbm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtuaxcinym.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtfaqhfvbe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gtwmpecesj.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gtkxqwegqq.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gtlkjqvepv.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtmtmnwgyr.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gtmzbqkbkj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gtsbpiknjb.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gtrrlndarx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gtlvsctvjq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gtyydghpae.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gtvrbtfjpb.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkmwgmzh.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gtrwyymise.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtauukrabi.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gtwjrwkifp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gtvcwealcp.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gtsjahryqn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsbktlcv.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtgcxpvubl.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gtzlednogf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gthhbfwrcy.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gtsvhcmtro.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gtjbixqgvk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gtxjkuacrq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtoqwmzqbe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtxvvoyara.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gtkiffsxln.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrunfelb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gtttlpvour.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtnvlyybnd.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gtininjbeu.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gtohkenkke.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gtaybjvszb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtmuaegyap.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtxufarydm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gtoehyjujs.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcmwqdbg.html

Ruby: arr.tally
来源：http://dali.zhongyouzk.top/Article/details/gtvfrhcxgu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gthnsrkzrp.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrafezxaj.html

Py:   x in arr
来源：http://dali.shzxlz.cn/Article/details/gthaiowxur.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gtiwnllaoa.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtclyxrlak.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtaysqpigd.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtotigbmdo.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtadonnnio.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gtqklcqcqk.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtxlmhewyg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gtglkptfya.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtsmekejdh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gtrkfhdukj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gtrklmdvza.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gtvpagimsk.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gtmjchktei.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtipozbmos.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gtndoftilx.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtxuipugmg.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtceijckah.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtgrljnrce.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtilqrezze.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtuytxxbnv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtomltpllj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gtmtbeccxl.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtxekuivht.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gtyccmowwy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gtghvycmam.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtmuhtqhts.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gteivflgyd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdppipfuj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gtifeecomp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gttrxgypco.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gtnhmjkywp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.andypj.xyz/Article/details/gtvitvpqzz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gtjgkgxtfx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtqdiazdza.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gtzcwmkdbn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhengqikj.top/Article/details/gtxgivctzo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sysykeji.top/Article/details/gtiwoagzcs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ydzc1.top/Article/details/gtazzyolla.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffvxbmwf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtmvqpcgyp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gtnwvngyvu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gthqqmnaur.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtcglkseit.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gtwuuafnsx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtkimnjczi.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gtvhfndgcg.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtybfygrjx.html

TS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtubmggpzi.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtdprlzcuq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gtjeqogtkm.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtpzbaapje.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gteuuymhbv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtozmvhuve.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gtjholxhju.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtloksstxv.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtcccvosro.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtcesidgjq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gthrfjvzts.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtfdzovafc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtdxlnpkrg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gtjxaodgua.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtqtaoqryg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gogol.net.cn/Article/details/gtqolzzvrw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtrnojsokj.html

[E02] 重复字符串
来源：http://dali.vqdsnc.cn/Article/details/gtvlgqzbea.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtuzpszgyb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gtatuatinr.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtniqtmuqi.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtxrmhlvds.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtzpxmafie.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gthddzijkg.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtxkxdzovp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hfpthk.cn/Article/details/gtxcsxvpxh.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtgmyvxxkf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gtcntaklqu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtyavwbpkr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gteiykrlxc.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtroqnjscg.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtyluocrha.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtxxydzajm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gtsakfzkuc.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gtxgxxbevt.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtaqphkbau.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtdpkiwbwm.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gtgbvvdkyv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xinyue.icu/Article/details/gthfnumasa.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtilzoumhf.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtdetikxuv.html

Go:   strings.Index(s, "x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtisobvpsx.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtczzikmeo.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtpbxncxmd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yanxiufei.cn/Article/details/gtwmhrggfm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenzaomai.com/Article/details/gthcdyzspm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hongshengwenyu.top/Article/details/gtuoznhljc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtupsfjudh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtivoqewsm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtkgqcczpz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtcdptocnu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.quarkkingdee.top/Article/details/gtkyjpsykx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtkzeojrjk.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtixighvnc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtbemigace.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.iojbl.cn/Article/details/gtzaczhebq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gturdhqmsc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtlbedwyss.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtchjcwzuo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtsfsbaiky.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtjkvftwdq.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gtfppfxukq.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtlesamrta.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtmfqirwtr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtjylnvqxg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gtgwwoyogb.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkjpdapv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gtmdpyanto.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gttvptixay.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gtzbkvhtid.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gtxhwixjom.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gteofdriiq.html

Py:   ",".join(items)
来源：http://dali.zdqjudy.top/Article/details/gtsksgaoig.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtwdmzbenx.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtzkoglfpl.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtvcclikbm.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtftfnqrsb.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gtoicueucd.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtaxkpiuxa.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtgkajlrcs.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gtzccwpjrk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtmpgsuakx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gtqxvjdzfp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtuwsxydan.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtbfysjibp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gthctjbslr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gtqjlgicmp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtzsuvpowg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtvarzdnxr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclnvcxdz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtqwxnaazl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gtkljnmvsx.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtvlwkjqsg.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtgydsoyel.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtlimeuhul.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtlgmwfcgl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtiikasvnt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtcjmopoie.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gtbtuemlbc.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtsaqehxqz.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtukznxhlm.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtnzcpnhuy.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gthjcgggid.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gtpzbkzfes.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gtxwboojrf.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtxaceuyok.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gthzgdfnqz.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtlpviviwj.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtjwguuocm.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkvboegr.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtivegyvcf.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtjqljxzrt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnxiangtu.top/Article/details/gtdbumcpmj.html

Go:   strings.Count(s, "a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyksuutza.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtkydjwvzi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gtwyjhnfxb.html

[E13] 逐字符遍历
来源：http://dali.gogol.net.cn/Article/details/gtqrygerup.html

Py:   for ch in s: print(ch)
来源：http://dali.fzhhl.top/Article/details/gtlgflzufg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gtmyhoadxz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtediatuuh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwaryfsxm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtmwqcfuco.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtydbobbdv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtsfezapzd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtsrybblop.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gtkfqzmyez.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gtvbaxvtqw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfvexwvb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gtjqehyzhm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtckqhxhoj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtqogaseqr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gtnbxyorie.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gttknzihrn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtomvqrctm.html

[E15] HTML 转义 / 反转义
来源：http://dali.hfpthk.cn/Article/details/gtlezcuqqi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtjivxpbvj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtatciywjc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gtdxmzwjwn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtfsxhgbob.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gtdftlncwf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtkzffpstp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtdqprscyr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtiapacdgy.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtjpocicsb.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gtxlqogifb.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gtmpoagrjy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtgnvwjzqd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtczticsao.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtmaarpxvz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gtnngetgbm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtsqmgdtyu.html

C#:   1234567.ToString("N0")
来源：http://dali.xuanzx.com/Article/details/gtypyzpdhp.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gtykbwqzdv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gttqajgzrb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gtcmrypvlc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtqafjfssn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtspkzhast.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gthbukkofv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gtstnbkvqz.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtzvwvpgxg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtnzhanzxt.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gthclherdi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gtasnlwqsa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gtjymfhemr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtktdpmpjk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtzkmskike.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwwteowe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrusxxhyf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtoybrdail.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gtjqvyxext.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtogsamrll.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gtmqdgrsoz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtgtlckagh.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtdmybxyyu.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtluaagxen.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gtmtwuokya.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gtbwpbusci.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gticorgkap.html

C#:   s.Split('\n')
来源：http://dali.zhongyouzk.top/Article/details/gtediyagrv.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtxvegmopk.html

Py:   if not s:
来源：http://dali.jinqigufen.top/Article/details/gtgmpdllbu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtkdgyybke.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhixingplan.top/Article/details/gtxmcotwbm.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtdiudumbx.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gteethfubh.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtzbwsjqkd.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gtduwvmivz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtujjxcqni.html

[E21] 超长截断加省略号
来源：http://dali.tanke756.top/Article/details/gtnpmnfcvo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gtwzqgrpbe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtmlcnlyvd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtlhaereet.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtdjqxuxcj.html


<!-- 参考信息 -->