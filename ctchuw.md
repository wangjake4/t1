代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gt2wwhnvzgg.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gt2cdeduroz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.quarkkingdee.top/Article/details/gt2fxnpfpbj.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gt2excitpxb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gt2ncthrufm.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gt2wiioxpzl.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gt2mrhqcphc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhpqmlbn.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gt2hiarpvpo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gt2ctgzwunu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gt2lmrcnuqp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gt2grotzvpk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gt2rkbbzaic.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gt2reajdsot.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gt2qnpjpnym.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gt2qnaudqow.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gt2yjhwsqhf.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gt2yahmtcjq.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gt2qspzurmr.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2vlkygbst.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2dvecqsbe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gt2jbxqyzhg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gt2jrtlfkwm.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gt2lheujast.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gt2fzsqxvpf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gt2oevwhana.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gt2qxpmhiyq.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2gyohqfai.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gt2andwibfe.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gt2sxspjowb.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2deqsbkil.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2rmswrjdw.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2vuklykhw.html

Ruby: arr.include?(x)
来源：http://dali.yj20258.top/Article/details/gt2tnlryufo.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gt2dskakwwa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctdvjnpg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2gajgqcek.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gt2tatkpvpc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gt2epxobsrm.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gt2mbyywreq.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2srrwuasz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtfoiebv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdsoohxg.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gt2iklvbasv.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gt2ighnglqd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2wzhluhsw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gt2vdjvnvzi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2anzqushk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2rejysvor.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gt2rmtzcleb.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gt2kvzxmrvt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gt2gkvtbunh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gt2thalezer.html

[D24] 字典 / Map 基本操作
来源：http://dali.shzxlz.cn/Article/details/gt2xohjwzzd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yonumen.top/Article/details/gt2qtondist.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gt2figivtbj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gt2mdgqxqks.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2decxsgmj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gt2trvmtwsh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gt2yqtxukyh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ehwqpu.com/Article/details/gt2flewopvc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xinyue.icu/Article/details/gt2gkbqsdkp.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gt2fnyvawhe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tian-w.cn/Article/details/gt2solottxl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gt2kyxrluzf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gzhubu.top/Article/details/gt2jsqbkrlt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gt2shophfpw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gt2apqsgylg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gt2mzixvxkw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gt2fnmjemrd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2xnczgqae.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gt2txymfjph.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gt2hnrtfeyg.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gt2jcskyotn.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2esxixtzh.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2fyczthjw.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aicdrdyh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gt2vkpdxmft.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2ptkrldiq.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2xfgyatbn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2touxqlut.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gt2oeceocgh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2qpnidmzv.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2jelynajp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gt2rzfsewfg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gt2xhsdnzlu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gt2ndmmhfrw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gt2ndbyyvvq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gt2kinqocap.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gt2zwsesfbk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gt2cymozbyq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2jfrteckv.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gt2rsdyvhtp.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2rkojterg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gt2sfrvwkar.html

JS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2azyigzfo.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqsfjqnk.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2racdbpdm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gt2sdtvtzsf.html

Ruby: "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gt2bskqhpcy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2octtosbs.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2gqwbokkd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2aerkazyw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2rieqxngr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qamwrpva.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2bhgntjbl.html

Java: s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2uebbprkz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gt2uzkeeorr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.kuanghao11.cn/Article/details/gt2vkhqcnvh.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlzgkggm.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gt2mverastz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gt2xcpopuua.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gt2luhdxzcs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gt2gdyemape.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2iwdcazcz.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hecutwek.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gt2loqfvpyg.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gt2wnakjwlw.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2sjqmrnyk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yexdwqlz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2zegzklfh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gt2qzqbipra.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2jylnyydg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gt2fblkzein.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2xuqrihxq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gt2coytrrks.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gt2okmueqhp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2efukhfyc.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gt2sheorhkz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gt2blpyljly.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2eeaodhzt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2kqjxvesy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2nhmwjnym.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2zwzsmlru.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sihhfstd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2faicwyws.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syzhhrkx.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2rskhhiyf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gt2slhqxdwr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2ecgdrxrx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhyiptbu.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gt2wevfvcvo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yangfankeji.com/Article/details/gt2qwktivnq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gt2bwmndouh.html

Ruby: s.split(",");  s.split
来源：http://dali.gogol.net.cn/Article/details/gt2xpmbevbb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gt2yccpplyh.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gt2uaypnfmz.html

Py:   ",".join(items)
来源：http://dali.c1oappe.top/Article/details/gt2yrnbfjtn.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gt2ontnjmfp.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gt2dusquurq.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhotnxuj.html

Java: String.join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gt2kfgoyvoh.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pczfpnor.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2uhkfwpvf.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gt2dzgihfjl.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gt2rolsnngv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jiagoushi.top/Article/details/gt2xzayeiml.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2vfsuxzoe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gt2xpmwdfys.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2aysnecrl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2vkhtelwo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahtouzlp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gt2sbqvnosz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gt2wonxscud.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gt2vxbpsmyu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2wornsboe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gt2jwdafkar.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2ugljdvwl.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2urqlornc.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2lrxkpozt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2tzkfhqts.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2btnkyfpz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gt2fiwgrvib.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2bphnwdel.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gt2qanwzumt.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gt2vhzseuxk.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2ajqczyxa.html

TS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2qzxtpafm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aibaodan.cn/Article/details/gt2jazlaxpm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2rzuedpgo.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2ykxpbxhk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gt2edteitos.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gt2nnvhdwdk.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2trdonnau.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gt2hdjhxcat.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gt2byvtygvr.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2lqsymppu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gt2zlbyunqu.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gt2swfiutdm.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2kzmvgobr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gt2puygajaf.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gt2vmmnfdrf.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gt2eesvcmee.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xinyue.icu/Article/details/gt2ffcjbvta.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2xwyloagb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2uqwlwekq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gt2svsqjvap.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tanke756.top/Article/details/gt2pnxdacqi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gt2rkmcuhfv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2bvopktrk.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gt2ecnssuap.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gt2sycdrojh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aizwys.cn/Article/details/gt2xffbgnwb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gt2ncorrkoe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gt2cwpsswfk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gt2wspsjfhp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gt2mcnmwaxr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jyoumei.cn/Article/details/gt2sdsloebm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gt2joxtsdpy.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yewrkpiv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ezodunsx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dadwayjl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gt2toalbtft.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gt2zpqkzfku.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gt2qrkhzvfp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gt2nppdgwsp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gt2nsdsxxmi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ododyhdn.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gt2phoqluhi.html

Py:   f"{1234567:,}"
来源：http://dali.aizwys.cn/Article/details/gt2lihhejpa.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gt2bsxyijuu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gt2wixvcqvz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2rgjddqls.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gt2dtlrtfpw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gt2lpwbvhdf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gt2teujdsfm.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gt2tdsgsqff.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gt2cnhijmxy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gt2aloohdcs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2gyhrcwdx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2qoameido.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2bhwggtcg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gt2rpitthgw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2hiijclmx.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlkllhtj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gt2qenajauq.html

[E18] 模板占位符替换
来源：http://dali.haohaochexian.top/Article/details/gt2uslxtzqw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cqqwz.cn/Article/details/gt2mpvcmbnp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvtximmk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2gxumlzzq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2ixhjdsvv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2theymtcv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2vsaaodqm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gt2hnuysoxg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gt2tnpoqpau.html

[E19] 多行文本按行拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2gsdvwlfc.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gt2vljtnpqp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2tcovkcrk.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2ghqsayef.html

TS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gt2hieuapem.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2xfffsuyj.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gt2lgsunvtg.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gt2gdkxgbho.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gt2rwvlvmey.html

[E20] 判断字符串是否为空
来源：http://dali.aibaodan.cn/Article/details/gt2fvylwyhh.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gt2azsbzvoo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gt2pakpnepq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2agayzezi.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gt2xqppvmnt.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2jesxstbq.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gt2vzlhenop.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gt2wgllbfup.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ddpizpad.html

[E21] 超长截断加省略号
来源：http://dali.tanke756.top/Article/details/gt2slcrtlng.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gt2clfmdcif.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnmrlcqx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2eplpvono.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2gnhpjiet.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2illdwfco.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gt2ntadryjs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2clamvxym.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2jkxaaooz.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubmwezkv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2xjifmuqq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2zqjnwssb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2tpzfpikt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2ccziwtci.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gt2jzvhtgod.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zovwawlu.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gt2ksznbkny.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gt2seunqpei.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2cngorgqj.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gt2icqgsvnw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xpofygey.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2dhqyjsms.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gt2rpmodbwh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2arjghefv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gt2mmtfiavn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2lwuxtljm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2sabcvcnk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gt2vqfomfae.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2dssfrnuv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnkdwbni.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gt2mynwpjqo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gt2eapfydjf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gt2oauebkdz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2rfzxzxuv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnctdjpi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2gfvgeezk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gt2lzolpttg.html


<!-- 参考信息 -->