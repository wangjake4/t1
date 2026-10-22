代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gt2oyckfusp.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gt2emzvtgsa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gt2jgszfjbn.html

TS:   nested.flat();
来源：http://dali.hammf.cn/Article/details/gt2rcfvqcom.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gt2wpkitndt.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbvpefgz.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gt2szbsgowu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2tvdxbyxg.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gt2yfakvqbu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gt2ojynremi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gt2vczevfdy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gt2xuqjgoxv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcdlqcul.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gt2ceopywjs.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gt2eueefjcu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gt2lzgiovrh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gt2frrujcul.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gt2umrocmrs.html

Py:   Counter(arr)
来源：http://dali.cucudq.cn/Article/details/gt2omlsqxaj.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gt2ncymsxem.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2ozudvkhd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gt2ufrofdoe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.9152youxi.cn/Article/details/gt2nsrnjwgz.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gt2hdbxnbmm.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuxsayxz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gt2xgjfepdc.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gt2iasehpuu.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2elqehoxr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gt2lznnzjlu.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2vvalcoun.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhrhdupt.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2xdcbbfpp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2esyjypyu.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uyaeykji.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvmoeph.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gt2rxqcxbzl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2nxgtwidv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gt2mwjuijma.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oumwlicp.html

TS:   [...arr];
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjeagomu.html

Java: new ArrayList<>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xirxxfrt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gt2qdyvsziq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmnjvwma.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gt2grwcrwfz.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gt2tgryxdxk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbohfasd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2mvufjxyt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2djytnuwx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2cfeaxnlh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gt2lkfafosg.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvlinvxp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gt2qjkvuqph.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2loksyujr.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gt2unjykzzf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ppyfmuqk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gt2nijfjrek.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sxryk.cn/Article/details/gt2ufyjtxow.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2kelcbokf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gt2pxrnnzbn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daxiang520.top/Article/details/gt2jxzapuwa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2jgdtxtiz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gt2vszvzjzo.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gt2ksvmjxna.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gt2ocykubfl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gt2gfuammeu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gt2lhwvqtln.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gt2nczgopog.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2qfteagfc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gt2zwvevuvo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctogubwc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2yzymdreo.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2evgpuibi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2piyrgabq.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gt2uycdfuwo.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2vbfclhnn.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2pahkntpm.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2ebejfiwu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgfzy.top/Article/details/gt2dmqrrbiq.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gt2okqcreqg.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gt2xejamvtx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vowujjoj.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gt2opgqffpj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcyuypcf.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oelfiioi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gt2ggewfbwh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gt2ycixieuu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2udjxaxdg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gt2fsknexen.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgfzy.top/Article/details/gt2hamovuod.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqmykpmq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gt2krouvtsu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2pwmnmnkk.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gt2gxgpytri.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2rhykmgyt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gt2hlmyrcuu.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2sowqdcrf.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2shgjukwd.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2qqoookde.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gt2olzcvpxh.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gt2kbffcysy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gt2oweuttnc.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2hsidyhgx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gt2cmygxwow.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2spmvqgux.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2xdvayrfv.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2eqaxltxo.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2zquehdql.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2hlufvkzr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gt2npnvbxye.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gt2quatgjbq.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gt2zylfjckt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2mcedbiqv.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gt2ghotwnzk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gt2rgmfnutf.html

TS:   s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2avhqduhg.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2knxtzrtj.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gt2sohtouht.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gt2ggltwnnr.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2kztqizch.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.meibo888.top/Article/details/gt2decspfrk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2gleagmkr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gt2vgbfacau.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2hufddjpf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vokfntqz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2ztgkzodj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gt2nqbaqvvf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gt2uvqibheq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2lxhiretj.html

[E06] 替换子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgksjcab.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gt2lmxcrfbb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gt2adzxuuti.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2jdepbamk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2adsosybi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2uhmdsxlk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2mzfznued.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2egkmhivt.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2wxdqcekz.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htvmhqvw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcbnweow.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2novbqavf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xinyue.icu/Article/details/gt2ekdjxkdk.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gt2cjrbtkhj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zdqjudy.top/Article/details/gt2odecvzpk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yenbixru.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gt2rxfqktpz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gt2lgcwujco.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gt2fhufyyfs.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gt2nioobtsv.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gt2yqyhjrjs.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2wvshdhdu.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djbighrc.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2nvhkbxed.html

Go:   strings.Join(items, ",")
来源：http://dali.sxryk.cn/Article/details/gt2cenbwiid.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2fqrwuotq.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2gcrulrft.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gt2nyofycrg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gt2xekmunau.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gt2zmgjubrh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2oyrzkhcf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhgohoum.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxbqkzvs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gt2ehvshnbw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gt2inmcodge.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gt2ghposxsl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gt2vbemojeb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2ipayvvsd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gt2obptigpc.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvdnzpra.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2jcpmxlji.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2afjiseoe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2uaksedky.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2penfoakv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gt2caexammk.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gt2vabsckua.html

Py:   s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2ycikupmd.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gt2bdmgqdot.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2wlqhjbmp.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2sdcunvaf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gt2bmbyvebk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2tuexvabc.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2ukjevtki.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2odidogfb.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gt2yejpecmo.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gt2ewloeilf.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gt2vouevuuy.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2zvyowdwp.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gt2efczvlai.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gt2kurqikts.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2jkxjhili.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtqnzqxe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gt2efswnjis.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gt2kicvjxuq.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gt2vnskfcne.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gt2vhrusttn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2yklcxgay.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glrlgucn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2qtxdkrtf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gt2rlofxvgg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gt2kgupvxzs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2alybygkt.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gt2pflwrqer.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gt2ystrarth.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2moflaolv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gt2bfyiwkek.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gt2nziyjjzz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2oxhsyuoj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gogol.net.cn/Article/details/gt2brxnucvl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmmzfvup.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2gupwecmd.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gt2ywbelnfq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gt2zmrtzobk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2qkyiwmko.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gt2jzwllghk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gt2krllbfvb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2ctudyvoc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2yvaoyrse.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gt2ajvqulgl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gt2eubefxjv.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bulgwoms.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gt2hfttuymr.html

PHP:  number_format(1234567);
来源：http://dali.tianlin.xyz/Article/details/gt2zutoyswm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gt2vhvpyleq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2omchulmi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gt2swksaenp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gt2nzppjlrc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gt2zyxziwkc.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gt2yqwjjjcn.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2jvlfktek.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.svipenyu.cn/Article/details/gt2tgralwrt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gt2dbybyjlc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2vrlpyhah.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2trxnteyn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gt2rdjeeaxb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gt2bafoylph.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gt2cqovaspd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gt2uvuhwxoi.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gt2wvkdhrte.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gt2rpynoozk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gt2gpuglwhu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2aubfzbgs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2qizvswlv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2tyyfvebh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2zkuuyteu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gt2qrykmtao.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddxwsbko.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnomaoyi.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gt2psvyxouz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2lkicjjve.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gt2cofbppsy.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2ahmcdcmx.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gt2zjxnqnkn.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gt2dgizrknl.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gt2wnvgjeyw.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gt2exxgkpcd.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbwlrbsa.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gt2dbjzkmxr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gt2yfgihgyb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gt2leengwgi.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gt2yvwhatgc.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gt2gcwecpdp.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iydhrhay.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gt2cxrwrrki.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ysaewqzi.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gt2boxstkqi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpzbhnus.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2hotejtlf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2bzbkvjnv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2mhkoqnbn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2wigyxome.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gt2yewxlyfh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2cozszczv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2lqudqusp.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gt2deuiudeg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gt2igvwwifu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2bfxbsdpi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2rxxsfslk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2zjerbgwf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gt2gabxzesg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gt2rhmeprnf.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2vbxrsnfd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gt2mpyakaha.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2qceiaxlw.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gt2cnqkiwkt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2zoepduoh.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gt2aoyvagax.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gt2koicixum.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2vwkdjbcv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gt2racwyvzi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwgfuonp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2ugbfdckz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gt2sovwcnkh.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2dcayutgo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2ajuurtpk.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gt2bzofgitj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gt2akpikypu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gt2wxsxdyzt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2dhacqtpw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gt2tcyisiqv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gt2ksexkrcx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gt2tbzkxkuo.html


<!-- 参考信息 -->