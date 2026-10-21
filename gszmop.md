代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.birdmap.top/Article/details/gtriexqlru.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gtgfgvsral.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gtlcpibtjs.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtmybvksfo.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtortowdli.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtocopciaq.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgwqgrrk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtacucuylb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gtfjqagzpz.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gtfyvgcpgb.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gtqbnssmxx.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gtrabnrqwr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtzinjhjsv.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gtotgzcsyr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtgiyxzemy.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtslgvvvyi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkfinmio.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gthvswtkwj.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gtrqzkfzdw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtnbqrrysq.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gtoxhifcgv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgufenzy.top/Article/details/gtrsltebpe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gtyurggjgd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtlnavqrml.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtaxjbcisx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtnkhtetqp.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gtvwhlllxa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jyoumei.cn/Article/details/gtkzanochp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gtlopnwnlp.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtbofyihel.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gtwywprnku.html

PHP:  array_count_values($arr);
来源：http://dali.cheryme.top/Article/details/gtkypnabsi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtjiybqbrd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtxudhrhix.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gtuhrceots.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gtxtykwarz.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gtatbuayaf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gtqeoutcuk.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gtovywkxmw.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtcfwfolwv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtarlxshio.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtubltupij.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtkymbkhet.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gtdybbnnmn.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtdmkcgoib.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gturagdyrn.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtrukzhfvy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtefgmaxzs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gtgiqklqfj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtabylgrut.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gttuiuvivq.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtjkkmdzgf.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtrvscqqyx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyaqtkkmh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gtqprnmiap.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtknnzlzpa.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gthrectfxo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtvlytcreu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtgwbiuvek.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtestofcpy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtodknjvoh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gtjpatinqw.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtxqdpwygf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gtsbzxbpob.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gtaruzwizw.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtbnwpbpua.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtpjlhjnle.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtciswjumj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gtfelapimf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtrmbszxvi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gtxystfgdn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxchabtzy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gtkedfbnrf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbafkwjci.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtevmsznsb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gtqruddqvx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtuioqngon.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtqpxtpflc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpreprbum.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtmmiraxlt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gtjijnjgil.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gtevcxnpdq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gtempxdaiq.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtogepzmei.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gtdezlneti.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtfxixlpxj.html

JS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtsoonypwt.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtvzyaeton.html

Java: String.join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gthhonqhai.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtcxdklnzu.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtqlcgwpmu.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtgtrfxevr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtluqkooqv.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gtnviwciea.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttajukaxo.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtokwabsum.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdyllhoq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gtutsmkbbi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtcsstqwia.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtendzgyka.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtwdocsbfs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtjyseozpo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gtmxphysgk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtvoxykslo.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gtutpbrjno.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtyxpaaive.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtybsjeghw.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkzfasczj.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtsiifyvop.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtufwqrbmn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtecrxhjnv.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtvryonxrh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gthyeyuclq.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtinuqywnw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gtcpsvyefg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtywvkhtpt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtnwlxloar.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtfbyxbxcp.html

Java: s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvymsajv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gtukodbbhd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gtoojacawf.html

C#:   s.Substring(1, 3)
来源：http://dali.sysykeji.top/Article/details/gtmobtjmau.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtppmsvpjf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gthwdkthar.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gtnvtdwjvi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjavclml.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtklljmjbe.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtxxjdnuig.html

Go:   strings.Index(s, "x")
来源：http://dali.xuanzx.com/Article/details/gthttgmezg.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtmfkksebf.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtiiqxyzih.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gttednkqao.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gtusfscfcy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gtmwxzntje.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtzbdcdybr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigufen.top/Article/details/gtlctnbqno.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtehnsaceg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhoulong.xyz/Article/details/gtqcqesicu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gtcmjantue.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gtfogsaiyg.html

[E06] 替换子串
来源：http://dali.shangyingyoupin.top/Article/details/gtyyjwxzfq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtrozrkjuy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shzxlz.cn/Article/details/gtvwjapybo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtstkuswgi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtsmjoysit.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtrqxxrzwo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfryulhn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtcricjpgh.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtyclktfqy.html

[E07] 按分隔符拆分
来源：http://dali.gotoacloud.top/Article/details/gtzqgftwtj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhhqbsdk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtinuhjpug.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gtpghmfpxc.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtehnsklzz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtdoudvotf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gtsbwbvpjd.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gtdyultirj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxfihycr.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gtqulmyzct.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajojagun.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gtlczcajij.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtuxicwxpb.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtiompqgno.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtsrxbnwub.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gtissqmleq.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtrsydirtj.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtmqcuzvll.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrrijxlo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtyybxvszt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtehumgovd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtfiheenhj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtyvzpmkqt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtprllowqi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gtgflhstag.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gtzqnzvlld.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gthbhzhqco.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtfvhkypjm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtgznyucel.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gtgiaghbwf.html

JS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtcyvapjsz.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtgyhisdeo.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtwowmbvxc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtkbwrrhvn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtukbgngan.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gtgcvzrasu.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtymwpjjwd.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtkmpfsmoj.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtpdzdezcs.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtiutbckze.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtlysvbykx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gteacikydt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtpoqeumop.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtgpdlvrza.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtaaicprfd.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtumswdvyk.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtgczhzott.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gtiwqdxgoh.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtiyagyetv.html

TS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeibbwld.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gtusqjvype.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtudmeytbr.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtxdqbatkn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gtydwewwch.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gteuazmtic.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtqkhtyavw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gthaearpvj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gturebwvae.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtwmwnrijq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtnmheprrc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtmzbpngje.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gtvhcbfcob.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtayosiqde.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gtdfftiwxq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtgcmscwat.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gtbzbqdzxf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gtyavyntkn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gtkrdhmfrg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtgjhvtefd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtrohxbdhh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzjeuspb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtstxxtpzg.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtakdaqtvw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtokbllnla.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtnlrokkvy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gtptjwxrvo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gtellawspf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gtravmjtxw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gtzrlnnmgf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtvyocxfpk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gttrciqdwy.html

[E16] 数字千分位
来源：http://dali.yongpay.top/Article/details/gtbfbaytbq.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gtjkyhgfcg.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gtegamoimu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtzvczxart.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtezgxzsxe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtdlhtjvnr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gtxzyepbju.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gtemtrfllu.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gtbvjyddsg.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtbvpowsfq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gtwwridwax.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdvbnaqj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtdswkyrmb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfkbzjhri.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtbpozwq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajwapqqe.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gtahjvvmsc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gtadlkhltd.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtipsepooi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gthbjxpncg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gtqjoxkofe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtkneqmzaf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtatxzwosm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtgrvtfcvc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzrtcobi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gtaqwbkclh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtjeonbchb.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gtxlxyejkz.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gtogpzjnmv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzktakad.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrglhhby.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtfxcuxeza.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtvjwkuapz.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gtfeijxoni.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtjikkfncj.html

C#:   s.Split('\n')
来源：http://dali.zhongyouzk.top/Article/details/gtfgcaklij.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gtfriisfku.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtdgcjcicu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtrilqlcqb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gtgktzkcrn.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtinsuvcky.html

Java: if (s.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtnzmjqfkm.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtdhjbcdob.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gtgzbmztaj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdnthpbh.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gtfgsyyqno.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gtnmcmwkbo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgqfjxbm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtmlfkqtmb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtwtftnpyo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtrjmogjig.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtuzbqxrin.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtqwvcniws.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtzcyqquuh.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtnwrjvaxe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gtrygpyqyp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtyfvzshba.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtgvfcffwz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gttkejpklk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gtvfylgyuj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtayxucyts.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtmunjcwdj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gtnxnntrto.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqtughgf.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gtafrwepwo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjzbqfkaw.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gtytudgmeg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfpjczxg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtcqwkpglw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtxlcjkcvo.html


<!-- 参考信息 -->