代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtmtiuvwok.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gtjhjqdzyp.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gtgiskhbls.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtpcahmmbx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpanpwhtb.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gtszurvirk.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gtbdmogilg.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtttmqguwk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gtfecmxcnr.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gtjektutuu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gtrsmlognl.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gtrwnmaxnb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtixvkwiih.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gtsgavkrph.html

Ruby: nested.flatten
来源：http://dali.zdqjudy.top/Article/details/gtsvwuvmql.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtbaddvanl.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtmvazabvi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gtwqlkskwl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtzfcbeyui.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenjidiqi.icu/Article/details/gtsmpkbzxx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtidglxdic.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gtzvzcjxwo.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtvshzdyzk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtjmruwjgq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsurfrtmn.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gtbquzmecs.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gtxqaaszbu.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gtrfxjdndh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtzcwrlkpt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtttfyglng.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gtirswmqer.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtaqyrdkxu.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtzdfnnmxn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gtcquneood.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtmozjrgko.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gttpkujjyy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gtuxgguqkq.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtjfonduxg.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtakacizkn.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtwbzssfrm.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtwscdooxa.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtrkvlfdhl.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtfoioadet.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagonhygw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gtoigjjado.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gthufohqxm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyxinvnq.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtcmqelcxi.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gtsbeibfvr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gtryxtkuib.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtkskcqlnh.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gtyacjruhr.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gtfdbnmxuc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtkkumasgw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtbuwzkixh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtejmyikfa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtzujpfmiv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gtmsqlopyq.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtnoxavqet.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gtmiqvlgdn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cheryme.top/Article/details/gtwzrfgjsm.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gtfjqotuco.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtvpyfxcuh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gthkbervui.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gtrennests.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtvuynnxdo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gtjxngmyud.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gtpxdefefq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gtgenfnhlc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gtclenhspz.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtmwgkvxii.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtpkpjfmbn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtxxlxaobu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gtmvmfaylz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.birdmap.top/Article/details/gtmelaoxik.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtpdldwfdn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gtvxhxwqbq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gtcqvclsta.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gtjwmuyxjp.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gtcbtnmsni.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gtvdwulcse.html

PHP:  implode(", ", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtoaripczy.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtifrzadaq.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtozixxghw.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesdrtdgr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtjpeelsbg.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gteudybbxe.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtmorshtzp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzsxvcxcr.html

E. 字符串处理
来源：http://dali.iojbl.cn/Article/details/gtcjpoznvg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtclfwqoye.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtfpfaquds.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gtmhjodslr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gtubjwlkrv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtlxsgdojo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtwpfkvyns.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtzdnnzxis.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtojplkbev.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gtczgsxcrl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtfvzmmdpf.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtnllcozba.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtyhpxnshy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gtqvhgkavw.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtslzmwfdv.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtovlmctsn.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttowwmhmo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gtylupifti.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtysrhtyhi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtycvvchav.html

[E03] 截取子串
来源：http://dali.tanke756.top/Article/details/gtwkerfkhv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gtqpvvkrla.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtwxaobbuh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtnuhbwqaq.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtozfsjdjb.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtsyqtfpgd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtqfgphoej.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gtvbwvshli.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gtnbnbrgqa.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gtjpltoilv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gturxxhdsq.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtirnqiimw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtxhpzhqcw.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gttwyumqto.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtcuulabqe.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gthjvfbmfl.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gttobfwrln.html

C#:   s.IndexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtlrsnpzyi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gtnjgzbhaq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtugpmfljy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gtjxykennp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtrkdqfliy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.bjfxy.top/Article/details/gtndoxfcra.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtcarebtmo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtmeimagyw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gtgegexfsh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gttpugpwam.html

[E06] 替换子串
来源：http://dali.andypj.xyz/Article/details/gtkbbgwgdp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzdjxitre.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gtkuksdkir.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtlleddhhq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtdrjhlabb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtymllgpky.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtgfrvawjc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtbiokgqhy.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtffetbnls.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gttuuzrnzz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gtlngpypho.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtvhjsuzuz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gtqnrfvksi.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtomcrvseg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gtwxqqzinj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.redwolf501.top/Article/details/gtlwzrooei.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gtczlqtsjn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gtgwrlknip.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtyhxihvdj.html

Py:   ",".join(items)
来源：http://dali.yanxiufei.cn/Article/details/gtxfbkaqzp.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gtncudctwt.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtqyyjwnqe.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtqujxldjf.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtpdgntwwd.html

Go:   strings.Join(items, ",")
来源：http://dali.fzhhl.top/Article/details/gtgvdicbgi.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtimyojexu.html

C#:   string.Join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtwasstxgm.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gtlphkgrhw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xinyue.icu/Article/details/gticikqhyr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gtnbkjlrgo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtrpcqttjc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtvonxyyaz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtmhgawlno.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gtzjdfpygs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gtfvpxwemc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtwtgfunmo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtmwkpjqdj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzkecoyx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gtupyjzxpa.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtapuwcpcw.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtjvntkboi.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtxgobiguz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtphowepdm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtrygfgjgy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnchfbmh.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtypkyrxjw.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtwudnggif.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtrvpmyfzb.html

JS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtgdyuttop.html

TS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtebpqcjyi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gtxzvwsixx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmsdpcez.html

Ruby: s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtoxotbotn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtypzveftx.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gtgoaidlgi.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtfaddgqyc.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtdiuoivii.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtysdlubfd.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtmdptzfya.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pengpengdd.cyou/Article/details/gtjbgriewq.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gtbgzqlgdz.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gtvdntrtxt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gtachrxzlk.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gttzgkxocr.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gtxeiegjqa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrgoqqqjb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtkrfyuike.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtvxoricnw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjvneodil.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gtttkjwyvq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtucfgprgx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gttavlplig.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gtbggmoeia.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtttqnlwcd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtnciipqfe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gttrrckqai.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258.top/Article/details/gtmtoalgky.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtsptwffjo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtrirysczk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtttcaxhil.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtkvdlkyvx.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtjgbhoqxk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gtvbmrskgl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtmtmjprzy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gtixdghvda.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtyzngpsnr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.316326.xyz/Article/details/gtiqgfxbee.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtdtuhjjaw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtujxixftm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gthzuqcouo.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtujklqvge.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqzjruob.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtyevrzaun.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfspctjqg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtgewuepjb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gttrrvtknh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuetiantiany.cn/Article/details/gtsgegzpzi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gtrbmrsgkl.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gtfmhwthka.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gtwqhzshiy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtyelzunmb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gtjmusfvuu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtibhuvhte.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtlojctuot.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtislsxrva.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnneegzi.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtqvdbxxix.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtezglnywc.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtxxoiwfnd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gtyenxvsqf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yangfankeji.com/Article/details/gtglzvzthx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtlaxavojp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtfqbgcbns.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gthcyrzxji.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gttevwcipf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtajwuellt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbvuinvu.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gthqdrsgjx.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gthwrkxrwo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtzdxvmomf.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtqlyygwow.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gtmniuwdgd.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtbdyuacdw.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gtscjieluu.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtvgxapmkj.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtcabuyuxv.html

[E20] 判断字符串是否为空
来源：http://dali.shuidangran.top/Article/details/gtscafghzo.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtbtrrafyt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gtpmyyinzh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gtgezxjdvc.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gtsnqtejxw.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gttajjxppp.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gtmadcpauc.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtxhhecgcz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtbemlzaym.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gtufehcavd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqbeulrt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gttnxisycl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjblhfqiw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtqckuhfhk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gttghxcdgh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gtdohnsovl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtzhbscyyg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtqewzaebw.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtutoyqcyg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gtsptnbzmp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtsvecrxxw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtwckplxuf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtmulwvypm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gtkhqoznfq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtsostolpp.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtuodgdomp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtijrtngql.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtinhgyeyv.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtqxcxnubi.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvanguyux.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gtucsrdxdu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gtvdzxqert.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtagmsvuwj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtbuekilru.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtwgehheua.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtdtvknsxc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gtlahacxxw.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtsvmwxzgc.html


<!-- 参考信息 -->