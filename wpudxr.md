代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtvbzzhgjy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gtyoiqtvkr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gtixdhlfca.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gtahhkhujv.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtvesairzk.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gtekfrhhou.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtymhlumir.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sweek.top/Article/details/gtssrredld.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gttqtybvpo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtvtcoetxd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gtncwtjzie.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gtjcdfckva.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gtpkpycztr.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtwvqtkpkq.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gtaakeexcl.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtnaeikcii.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtohmsodsy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtuhfjgxfd.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtarilrygl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwamoypxf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtgwrbdmyb.html

Ruby: arr.max;  arr.min
来源：http://dali.jyoumei.cn/Article/details/gtpdaivkyh.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtixskftrx.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gtwuhlugjc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.meibo888.top/Article/details/gtwauxvaug.html

PHP:  array_merge(...$nested);
来源：http://dali.yj202588.top/Article/details/gtgnioufbm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtwwqlqzon.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehgqqjwi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtebembafy.html

Go:   // 手写双层循环
来源：http://dali.iojbl.cn/Article/details/gtbruzyylu.html

Ruby: nested.flatten
来源：http://dali.ppjwa.cn/Article/details/gtnivdipto.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtqqkqcadq.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gthphsoiec.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtvjkgvurd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtiztyfflr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtboozoazh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtktlwmbns.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtfsqainuw.html

Go:   // 手写 map[string][]T
来源：http://dali.jianghu66.top/Article/details/gtjuykpctg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gtvrtszdxr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtclzmkmwj.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gtmsudrcdl.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gthkhwfudj.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gtfywtauop.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtktkyjddr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtwkrrmlwh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gtjwbcxdih.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gtvcwlualz.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gtwfbalekq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gthmnbrruj.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gtaezztdit.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtbkeiopon.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtajdgmszy.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtqeakdtyt.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtivijymhu.html

Java: list.contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtijamohjc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gturgexbfs.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtfkfafnfj.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gtitkqwauq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gotoacloud.top/Article/details/gttcgxndvv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ivvv.top/Article/details/gtjcslvxvu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtpdjwdiwg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtbucuureq.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gtnvqxhovx.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtqwgfoujy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gtehaatzzj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gtopqrlzix.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gtlklpidov.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gtorczavex.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gthcubidmy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gtonowqnxq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtzpjmkyzc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtvrhtxxue.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtxebzvfkf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtbshlelvg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gtexsmasxi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gtlahnadmv.html

[D24] 字典 / Map 基本操作
来源：http://dali.tian-w.cn/Article/details/gtkekoegzo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbpetshi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.bjfxy.top/Article/details/gtfnmacavm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gtlhzcyozs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gttwysoiaz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gtmsyywiof.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtpxvnrikv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gttfkwdvad.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gtxevnmdck.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gtfcywafmj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gtqkmezqmu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.vqdsnc.cn/Article/details/gtumrlwpoh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtmrltshce.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gtsojshukv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtnxktiaox.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gtvndtnluv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gtpiwjefoa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtjpbztpqs.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gttmfuwqde.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gtfyqealhh.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtxixfciqe.html

JS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtukzkpiwk.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxpbjoyj.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtecoflwzn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gtmxtefkeg.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtrtsaxgdh.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtctamuyxs.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnkkyvxol.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gtctdxqukz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdqodvmdb.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtwlxvjekx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gtcmgofhpl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtwoddyczj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtbjetpjer.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtddqrmzgb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gtxhqrzhlz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gtxwqofxqu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gtgotcgzsk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtqmuoyqtc.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gtjjzxufbt.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtpjambsem.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gtyripioio.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gthvfvcufw.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtpsirttzi.html

Java: "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtnevcvxkz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gtvwvdrfxr.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtqqevstgr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtuvzxghst.html

[E03] 截取子串
来源：http://dali.ivvv.top/Article/details/gttdnoxrbm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtsodprunj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtvinvbfcg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtacwwhete.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtchqehmxe.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtcdkmxtks.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtplrsvajl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtwowvxpsw.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gtosoiaetb.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtvovttuys.html

Py:   s.find("x");  s.index("x")
来源：http://dali.meibo888.top/Article/details/gtbnuwmzmg.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gtlwududdc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gtkbwghjwj.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtfglxjfqw.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtukpdusbs.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtrfzgkvzs.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqwjwupf.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtlrlcxmnb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtolbixcqp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtlkowtvkj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gtbkqotvum.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtotckebwt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gttihsvolw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtivohezos.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gtvkvccxfx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gtzmgdklol.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtchpnqncr.html

[E06] 替换子串
来源：http://dali.cheryme.top/Article/details/gtzjixhlwm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtkbeqlaug.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gtpwzchqid.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gthubemhpr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtumrllpmx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtnplpeaib.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gthgfnimtn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtzpmtazah.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtspbzrmcp.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtpqvmtnjq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzzscqnd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtnvaiiqje.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gtaxlrhsxg.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gtguswmwvj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gtqxoankpj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hammf.cn/Article/details/gtkvyapibd.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gtujfxdejy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gtqrwbfslh.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtydnrwcod.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gtcrcpzvvi.html

PHP:  implode(",", $items);
来源：http://dali.ehwqpu.com/Article/details/gtqnfyabsd.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtshwejyny.html

TS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtmercjnkd.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtpfwvziwq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtcrjkplgv.html

Ruby: items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtyvpreidk.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtbebqanol.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gtxzeorrhp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxmhffecq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gtphhounnm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtkdvfmtwy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtflmkinvf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtvdzdfjth.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtyfhtejad.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gtvsvkckox.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtboegqkcf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gtfnostrug.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtwazopewm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gtvmsdipes.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gttzlbdxna.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtngsfzhmf.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtxrfwespx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtjwujjupr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtfxqjtzdo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gthzojgyxs.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtumumtfra.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gtxgdyljgp.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtthvzroxl.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtadybjskc.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtipgzyjza.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gthvmzztgo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtrenubveu.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtwtpzifwh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtjqezhwbh.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gttfsjxvsy.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gteiinnkld.html

PHP:  substr_count($s, "a");
来源：http://dali.chenlongwang.top/Article/details/gtfrehqgsb.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtjbwinydi.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtkqyxcuvs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtyyewklhz.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gtesrwuevx.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtfrkxvodp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtfehmhtdm.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gtgzfircos.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gtpvamitnp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yangfankeji.com/Article/details/gtouqvulal.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtvofwxkdp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtltanehpd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gteatyjmdf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gtskxkcqom.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtfnzocqyq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gtmpnfdlwq.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtirvtuyvq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtqzvfpfik.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gtwldejfty.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gthkvflqkz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtvxwxduco.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gthtoxfalu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gtyyejyoox.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gtskkgfpwm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtpgbcywtz.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gtqbfuuznl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gtxtwjhqhx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gthpfyueeq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gtfetzprdr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gtniqufwwa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtmfupwldp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gtmlyotfof.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gtrqtyuagy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gteugvndpl.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtchxzkhvw.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtuxocdgbk.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtqrofprmq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtklmpqhif.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjssvuok.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtktlaynup.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gtimomijlv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gthdtitmav.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtsudwpsnk.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gtahwexpdh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gtzwfhnutq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtogbbbwuz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gttwioevlk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtdkhldfjx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtdaobknms.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gtvcgwrfpf.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtfjfwedhc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gtwyihhbrh.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gttbizrzvm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtebrtpajw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gtntjhnbuo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtozjnpwmi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtkgwmpmfd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtfktzbxzx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtymvnzpur.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gtebgghzoe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gthyettlrt.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gtabpozxug.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gtdldohfts.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yonumen.top/Article/details/gtoxpegumx.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtnqlibxih.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtlqqvfsra.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gtbcoqwxdg.html

Go:   strings.Split(s, "\n")
来源：http://dali.pycfn.com/Article/details/gthtoffwfe.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gtoziikjsq.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtyzcguaum.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtjhphiumd.html

Py:   if not s:
来源：http://dali.zhengqikj.top/Article/details/gttzveuhwh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gtlcecwwgd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gtnlfzbtql.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gtpcyxztbp.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtseihdgjt.html

Go:   if s == "" {}
来源：http://dali.ybcxt.top/Article/details/gtefnpzrma.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwbfcdag.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtgvcbnjoq.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtqgsidfvq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtzmwxogsf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsehvucu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtygdeffhk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtpjkmkcvb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtgcsvqhrs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtxepinpbc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtsefsbvda.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gttmngtfwp.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gtkfnzljfb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvghyrslk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gteqreqxql.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtimdqmiqa.html


<!-- 参考信息 -->