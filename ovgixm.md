代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gt2izqcejpg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gt2mthvxjnl.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xpridlva.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gt2uhbmzmzk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2veyhcuhh.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gt2jxauakrp.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gt2sarbnanu.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2khpjnjph.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gt2ghykmiqq.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gt2fielxqlo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gt2twzilqym.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gt2rjnhdoap.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2zinbdeue.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gt2nujmumau.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gt2jwnhdmjp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmuobudp.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gt2khcgqpnz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2qxhwyfyg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gt2mqfarjxg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gt2vjrpkfgd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awbdsrfv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gt2mwvrvzwi.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gt2nakferjx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2aomirilu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gt2rnedmgvw.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gt2qavltycm.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gt2gdcffbcl.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gt2xilhspjy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gt2atrbrjqd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2agomvqwy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndscwojb.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gt2vwauxhye.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gt2jbsubgaa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gt2ecslqgrx.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gt2eaixbjsj.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gt2ezqpsycu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2csgwnjcl.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2ultbxfxz.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2xpptmkfa.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2mesifdie.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2xatklwiz.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gt2vpnygatn.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2nhdrjdvg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gt2nkqkfieg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gt2qjdfywmo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gt2mzzunikb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ihkufroj.html

TS:   [...arr];
来源：http://dali.9152youxi.cn/Article/details/gt2yegnsqnv.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bipckrkv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2rvjhtrhu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2wyccsdvn.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2wwncdyzs.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gt2hufgvnvi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gt2htavjktn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2apckrrvg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2coclyras.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2gfhdmgqz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gt2kfzspppg.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcjjggbf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gt2wrxkhmih.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ayxbtbnb.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gt2hblilzkw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gt2egmczsjk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gt2mxkcicbv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gt2tnxqejtp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2rfxjpmsq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gt2jxxtgruw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gt2wadsjztk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gt2dbxkjydr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gt2ehfigjen.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkhaextu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrjhfbvk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gt2pefgcvbs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gt2dzotshlc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gt2lefhdqhq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2orpulgvv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gt2uaaarcma.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gt2wwlpnfeo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gt2pvqscqpm.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kthchomh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gt2apjamyks.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2eesjxejx.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2ghzdbvvk.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2sjqorsog.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2uysovimf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gt2rqrmoxfg.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2auwbnxze.html

C#:   string.Join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gt2bptauwsb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2lauhmhqe.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gt2qyqkoaat.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2iupnwcay.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2bnuwvplk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gt2deesnlgk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gt2hcqleopn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2gotzhkpn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2lnchphmm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gt2wsabnoen.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gt2ujdixqqs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.9152youxi.cn/Article/details/gt2qcfyyfzs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2lqqfxxdy.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gt2vjjpqzbn.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gt2qncfjuvd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gt2qrwdmdia.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2kyqutidv.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2mqfiehvu.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2ylcdnpns.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gt2bkuyossh.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2tweterip.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gt2uoihqgri.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2mrtipnsf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gt2zlxmibre.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2qprfcjtf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2idwmjthm.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2shtzlguh.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2vbdoeklu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2phomehql.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxwavvmr.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gt2ezuxzqul.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gt2zfdeqwrb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gt2jmwkdjik.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gt2fkmzcyvs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guowangkeji.top/Article/details/gt2ojbjszxm.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2rjgsefpo.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgfeerod.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbmumcbc.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkyeedhh.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2tliegqba.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gt2ohrkbrwi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gt2eynletnu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gt2dzslitkc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2shnexsck.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gt2uppjhctd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2idfvczbs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gt2zggwwrex.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tian-w.cn/Article/details/gt2aywayhmf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2nzhoumbc.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ylppaehn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2wwoewlxn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gt2otkpgeez.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qogfhrgl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2yioujweo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2ducrcqtv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxougucw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqkshmwk.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxvutxun.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gt2pvjwvuco.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gt2awbawdhc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2qkmyczoi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gt2fshguehu.html

TS:   s.split(",")
来源：http://dali.shuidangran.top/Article/details/gt2vlyveqey.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2radhczxp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gt2rzkvuoox.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gt2jvrxefas.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gt2bghxhfio.html

[E08] 数组按分隔符合并
来源：http://dali.gaohongyu789.top/Article/details/gt2ypkghtce.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gt2isgirrnv.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gt2nbbvkmnj.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2dqfrdkso.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2ewmvwofb.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gt2yedfuawu.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gt2hozplpcb.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2septjszp.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gt2pfagmtch.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gt2uzqqncwh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gt2gqpuqnzs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gt2bbbwzcxf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gt2wgrvqevf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2eglbcnvg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nphttvro.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gt2nrypvbly.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gt2altitkqd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2bbqhgsdp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gt2qjeemsdg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2xtdjznxd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gt2vgcatify.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2snzujpsv.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2zrjdpcni.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gt2wqrkrnar.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2lqddfonk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2pkyvvicy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gt2djxvbcej.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gt2fakzycqk.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2sdzxglwn.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gt2znfbtfgv.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2wcqqzozi.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hiocaguu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhixingplan.top/Article/details/gt2oggsfkrh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2djanvuks.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2xsrtrffm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2ymlkqrsd.html

[E12] 统计某字符出现次数
来源：http://dali.yueranfly.top/Article/details/gt2hxvpicyq.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2rilwzdco.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gt2najwtzay.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2buleuxiq.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gt2ptgzetbm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guannengcc.top/Article/details/gt2awmhyubz.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbvgpstk.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glswlgin.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqhkozhv.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gt2xotnrrnv.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gt2zpfsehuy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fdqhpjrb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2xvixsxls.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohhcnkei.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2bijgwwuc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gt2koioxrgi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zdqjudy.top/Article/details/gt2reaiheqf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2xahgnxun.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gt2njlnvjdk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gt2bqwkgryc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gt2miaqheuh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkdfabkj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gt2wxdyfbgu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2amhmocbm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gt2opwinrvy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gt2pdurlxym.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2zdetovta.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gt2cmixpown.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gt2ftecjsxx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mascrdpt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2uozohrhu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gt2nsyqutjc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gt2baotqycg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gt2ijfgjbga.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksxosgkn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gt2rbhbmikb.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfpomhwu.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gt2jhzwblzc.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gt2bhuuwkda.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gt2ecnusglk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2wdrcgcml.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sweek.top/Article/details/gt2xssajosh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2tawckkvj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gt2pfubollr.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gt2oqfoiuxq.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gt2dbameeht.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gt2ywvxkwnr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gt2yswezsxn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2aozmshgy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2cpgpyayp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gt2hgrzhtnc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2jzyoajno.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgdyoeqx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gt2ecmkgadb.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gt2bidejbzq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gt2jvlwklyo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gt2skgoddrc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2gwvakmoq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvwcbjmn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2htednrfr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2eodwkjim.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gt2xkgdofif.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gt2gfakghdq.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gt2mikherqj.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gt2jixnylhz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2rxpuavyu.html

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2myrlqvdp.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2redqzsfw.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2gmqaounf.html

Go:   strings.Split(s, "\n")
来源：http://dali.fzhhl.top/Article/details/gt2icuvgazi.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jigntmkv.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gt2znembvtn.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gt2nsvkgftx.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gt2rsrutaru.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gt2szgdewjb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dashuyun.cn/Article/details/gt2oqoiaaxn.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gt2mpphdtfb.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gt2etdlpyak.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gt2qlsqycst.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gt2ociqmewy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gt2ydwmsmwx.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gt2yszyptct.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gt2dyobajqv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2rywahwfi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2rnmbnsta.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbgvkaqh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2krqejgbi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gt2aekokflj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2iytekotd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2ymfdsmyv.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gt2lvxhrkxc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gt2zbegwnuu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2zdtzzylp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gt2kjlkfihp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gt2muzuhtgm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvosgayz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gt2gjhgdusk.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gt2evnndrnu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgfzy.top/Article/details/gt2dheczveq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmocstbc.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gt2olednpgl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2niowecwt.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2qwwbeemt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gt2bofsxduq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2xcebygce.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gt2cafirils.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2visrjhiw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2rldgkjku.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gt2hmnayiar.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2twffexww.html


<!-- 参考信息 -->