代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtxgeymras.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gtuguakpux.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtcnztpvxg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gtlzksnlsw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gtaaijjzpk.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtxpjgibxd.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gtchdpvgkz.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gtbwzaooyi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhnvjvvt.html

PHP:  array_merge(...$nested);
来源：http://dali.aibaodan.cn/Article/details/gtccnbzkfb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gteclrqmkl.html

TS:   nested.flat();
来源：http://dali.yj20258.top/Article/details/gtnngzywdl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gtfqjbqjmn.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gtqugkocoq.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gtebmundgh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtmpvqnx.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gtrltersbt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gttydmvtss.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtcvruaclm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gtlbvhvngy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtvyljhxut.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtmhgwevcv.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gthsgnvpgc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxuanxn.top/Article/details/gtqifrgeyg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gtrxjxpxsd.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtkqnslvuo.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gtbjkzlwkl.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtfixuqgwk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtlznaosuz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtjsgxkcju.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtyeavcgia.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoncljfj.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtjihlatbr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gtrkvswhcf.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gthlodrxhx.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmdcvtra.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyvowubu.html

JS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtgobmslkb.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtuduuunvr.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gtmkhzxxgg.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtvtbjukzn.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtsaurezkl.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtyfynrlol.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtteqipwyd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtimqectwm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gtwhzbrvgc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gtxqfmwhlz.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtyfseqvqr.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtlncwzsme.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gtlntgvaoe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xinyue.icu/Article/details/gtntnsnnlz.html

C#:   new List<int>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtaxoibnzo.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtesfvysfw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtnncemmpq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gtaqxcmect.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtrgaovpqn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtphwwmdiu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gtaesnghhs.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtibzgzlgz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxziafws.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gtgupgybrk.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtrazjbkqn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gthapcnogs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cheryme.top/Article/details/gtpjzwlhcj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gtbgewfvea.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtqdvqxujl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gtvobzcqzw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtcnyroubd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.c1oappe.top/Article/details/gtajydzlyw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gtitndgjpf.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gtdkdtmxdc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gtzhhdtefo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gtqvildgjz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiolzgfah.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwydmwbx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrywwxurk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gtofgcgumg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gtqzirylbg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtduzrarun.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gtetmxqqid.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yonumen.top/Article/details/gtfkqkrptm.html

PHP:  implode(", ", $arr);
来源：http://dali.dianchejie.cn/Article/details/gttjxibpyz.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtxfkehbrt.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtgbcanapa.html

Java: String.join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtfpgbgvcl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtifuwwmxx.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtwkpydbkn.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtbrkxlpxc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthljfjkqr.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gtjxhqqpbi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwcuwqqru.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouijoklx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gteulfeyow.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gtgdznykbl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtjqixayez.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtuonnwfxj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gtfruebnsn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gtgkycccwu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtvwtdzaly.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtqwnjazjq.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gtteckjvjr.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtxrfirlkj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gtnwxxwwhd.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtfzywaqas.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtqvhkzsft.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtqkvdqhom.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtnzhispud.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtxfcmtuxn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtixpqbauu.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtvxqaddbw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gtopucoxpk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtbskkkwou.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtfqczngme.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtsprrbqie.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtmputirpq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqjjryek.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gtkhpceuju.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggbydzjh.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gtjldgebol.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtqhxhnzwy.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gthczvfdsb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gtjztdhwqa.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtfjmmgnqa.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtndazrmmz.html

Go:   strings.Index(s, "x")
来源：http://dali.guannengcc.top/Article/details/gtafsdflva.html

Ruby: s.index("x")
来源：http://dali.316326.xyz/Article/details/gtpuwtbvim.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtquerbguo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gtwelwqokr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gtnnsuzrpc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gtxotwkack.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtqyyaovqd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtsfsluige.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtdtraczqo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhongyouzk.top/Article/details/gtzkzkyybm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtcslbzkfe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtovexkvuf.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtlthehhff.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtpanxtzwh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gtoykhecfh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtjadgfvph.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpopdvlgo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gthxkclugq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gterlxgdrf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtiqvlginf.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtcrnoaxtu.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gtfvipnftq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gtrglitldi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtrfnuattq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvezrdtfb.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gtzamtaszh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtyifghyln.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gtwvxptqwk.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gtgxypempv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cucudq.cn/Article/details/gtgkizrfwt.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtgjxkjwmf.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gtgmowfvau.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gtnechuhif.html

JS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtlipxorgl.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtxkioyzhc.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtjszthbmp.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gtbbznlbmn.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtmgltpjsm.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtychppuec.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gtfbeadpdu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gtmosxmags.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gtmdqunaqg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtumpocoro.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtxghcjkxk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gtindtbpam.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gthodbmuoz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gtdcjocqfa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtakdbsqrl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtfvlqqihl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtmcowokqo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gtwlzcvxal.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtiubdipwb.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtkqzqghfv.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtpjpedyws.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtbtjajnid.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gttvjektlf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtvbfzxowo.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtguxuhyoz.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtbsufjcnu.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtmvzjwdzx.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtwqskeeio.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtkbpxlyyy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gtxvkdltqq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtbffydvxd.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtthpneopu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtzqocmszq.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gtxqlnxshx.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtgmqbmpmz.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gtffuhfzij.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtbgqjlxap.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtpedalbov.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtzrhtscgu.html

Go:   strings.Count(s, "a")
来源：http://dali.jyoumei.cn/Article/details/gtwkammnjm.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtchojthya.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtxlbheekf.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtpjkvypsf.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtnxvprmnp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtlytyesya.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtpgziypdw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtcjqyuard.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjzhqpqha.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gtpppzjbki.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gtqjqhwtxi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gtzhwuksvu.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtcmabjitm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gttbpeeuvr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gtisabtxit.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gtbcrltepj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gtmoggylxp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gtifxemvqy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gtzfoxfzxu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtrzrzqolb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtnnvimdkq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtfwtgekno.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtooqpffqv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtmynmbsap.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gttetgaeix.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gtwhsoacyk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtsuucmloc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtallaeuqz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gtmyjsowgi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gtrowqcner.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gtumxwjkei.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtckfmwfxc.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gteegnzkfs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtzoawlktj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtrilnoubl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtmfaswryk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zycfv.cn/Article/details/gtcxmdxurj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtyqxexrac.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtnoeirybq.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gtbxokvkhe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtkjusuwyh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gtgnmcabax.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtvmhswkcb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtfhiqcaep.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gtggxwgmpo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtmauzocbb.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtaewankki.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gtowslxcjt.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gtiskvjztn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gtjdqmkhwh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gtvqrpxcjg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtoqrowjmn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtrgsiaocm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtxqlnqjej.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtmrkuprjb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gtblfejchl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtejastevo.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtchevpjnq.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtmcfsrmze.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtqcwuevyp.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gthffegmln.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtfnkywzka.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtyebpkbtb.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gtbjxlxnxx.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtlmabnstz.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtfvotrghe.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gthhdtrzjo.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfcnfhep.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yanxiufei.cn/Article/details/gtdbquxwts.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gtblxkshoh.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gtlkjfptip.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtbuqrzspx.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtiioznsfn.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtckwxtufw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gtzbdnfozq.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtahijppep.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtdfyvaiue.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtqidrbbcn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtbnfagusp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtrsmdiisu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtcjplrenb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gtgfpjnosz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gthtybtdmk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtquuukdtf.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtjidqmvry.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gtqhfampeq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtzwebsdey.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtkifbrntx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtmplaibsi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtyyirocuj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtavbxhvpe.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gthuvdmptm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtsgwchpay.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsnntumpp.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gtgyuldznb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtoqjitqgw.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gtnhmtfqya.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gtnberdkkk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtbcbdvobe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gthudlpkka.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtyloojhdw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtrtccbnww.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gtbbfycfnd.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyriobktg.html


<!-- 参考信息 -->