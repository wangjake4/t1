代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2brzhgoop.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gt2srdqqwaz.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2wvgrmlva.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gt2cceghchz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2swktqpcs.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gt2uzbzzsus.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2kcqtqnpo.html

[D18] 扁平化嵌套数组
来源：http://dali.hnxiangtu.top/Article/details/gt2ujmmpvbb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gt2icxcmgmg.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gt2frkviqvm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gt2mdgkaieu.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gt2pwvzjfqg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2puiwndwj.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gt2botvibdr.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gt2gtsluodx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2zjszgmsw.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gt2djiyidym.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gt2izgzjxzu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gt2qoxdmgka.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gt2vhhtrkmw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gt2fdurgvse.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yuxtirda.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gt2dzmmsdte.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gt2sqtgjdta.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gt2twfbfrca.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gt2vexxaoey.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2zjuaxruy.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2giduuomf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cglvuowr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gt2dakxiery.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gt2yyfixzwd.html

Go:   // 手写 map[T]int
来源：http://dali.quarkkingdee.top/Article/details/gt2yptcvwjh.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycgswnts.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gt2rydermny.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gt2yxunwrwm.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yszikmzk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrldogzw.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2awgebivu.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtlefbrn.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2zlyqmntf.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2acvhnhkw.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gt2lnfsrmea.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gt2negtrvci.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gt2akkfgthn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gt2zautywnj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwgkjbay.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2qcxvlavy.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gt2uswetjdx.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fczynthh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2zrcufehp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzgqgpoq.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozdyajuk.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gt2aoleohia.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2evgknnsf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2wemfoxvy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebvamlva.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpmmuqz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gt2kbrmlyle.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gt2uuvnhafe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhcfbxha.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gt2vlvxwunp.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gt2aizqeddb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2rsqkzpeq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cheryme.top/Article/details/gt2mwyiwylb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2dywgvzau.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2jcmwyoma.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2yemxeasq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gt2lthulbnu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gt2abannenh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xinyue.icu/Article/details/gt2nywiqavh.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gt2vgcpvclc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gt2gkozyhrq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2zctmhnmc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gt2jgfbeatt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.andypj.xyz/Article/details/gt2rpzkyaen.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2czurcifl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gt2ouqvfqdn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2epbqxauo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2oiveuhav.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gt2fwvcgdqj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2yuoczrln.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2thwunber.html

JS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2npaemswz.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2lxfdhkph.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2leqxyqjx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gt2jwmahsek.html

Ruby: arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gt2jcxodhdf.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2rtnwvagk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2itrpojyc.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gt2sgnruvdf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ydlgzlwh.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbxssjub.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gt2awbtzkpg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gt2dfxpeiyp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2kwcuvxdg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2djlwllgn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2uegwwlzu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gt2ggtzdtdm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gt2xarbvjqe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2gltzyksc.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gt2uymytaeq.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzpdawwo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gt2nwdssdig.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2lbvjaakh.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2uhjbegis.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2htuosmom.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnhcntzc.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2wqwylgpw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tianlin.xyz/Article/details/gt2zcsdnjqv.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2duvuqlss.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gt2vsfohejp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2fkaammen.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2uhvukzoa.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gt2ibhgwxfh.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2gxkzqciw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gt2vbnlwzzk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdwdbhf.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gt2nvcezjzi.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gt2qiuabhwf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tanke756.top/Article/details/gt2tgqgivlz.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gt2yxabhnbn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gt2uqlatjzu.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2kwvdjmcp.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2tcemtbfb.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigfzy.top/Article/details/gt2dqwlnzui.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2pxgzldsf.html

C#:   s.IndexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2ocznrdwl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2meftgoxn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2ozsbzrfk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbhtpddl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2qqjkdiki.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2ijmmqtob.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfofwffu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gt2rieeamkp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrikkxgu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2hwlccemn.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gt2cfvqmzfz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gt2nqzhvstx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gt2uzkaayig.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2ifzdybuq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2qibgvmiw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2owacgixb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fabjbsnz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2cdxbabxa.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2zlwlaldz.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gt2tdhjnlkg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gt2fdfwvikg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2okjombsv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gt2vcrvnnmb.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gt2dcrbwgqm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gt2pjkcosqm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptsmpvlo.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gt2thwdwfyf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gt2gmvhaphn.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gt2lhnndlyz.html

Py:   ",".join(items)
来源：http://dali.zhixingplan.top/Article/details/gt2alewqtlw.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gt2aizoxgei.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2wfruazlm.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2zfrjzdne.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xiupugpe.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sarnkeqh.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2shntpnxt.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gt2yfxiebpc.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gt2owkotesu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gt2wkqqhqtd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2rzpwikiw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gt2hcsetxzj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gt2ulupudia.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2bnbysnxx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gt2xjxwhckr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2womkttoq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2pksnbjmt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gt2qswjaejo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2qarekvre.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gt2hfjsgcnm.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2gprirdyh.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2bensjfcs.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2pbttckce.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2maoqprov.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gt2uaizqxnx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxuanxn.top/Article/details/gt2nkvtghnp.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfcvukzz.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukaambvg.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2ciodsddk.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2allntzwd.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2pmewzfgu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gt2vgjoexqq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gt2gevbzqoe.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gt2miobtxtt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2vwrbgqap.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2rwevfkdo.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2gjabibzl.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbcwanuv.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2gblwhudj.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2wydspqze.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gt2bljjynnj.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gt2tgpqmevw.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyackbrl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gt2yzajgcnr.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gt2xugiswyf.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gt2mdjuaako.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rngfjqoa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mvvxnftu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2rzfhpkxz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cheryme.top/Article/details/gt2ghrfnubu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gt2lxyqfbcz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gt2oqnoqwap.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gt2vggirbna.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2eogrpvbe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gt2ibstxgrc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gt2ipblnmbw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gt2juntykis.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gt2tnmsagga.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiqrlwq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggcqqyri.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gt2biemejkx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2ynvnvhst.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gt2wykepfpi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdtmuhka.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.mhx1999.top/Article/details/gt2tvwscxxb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gt2mwlgbnik.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gt2gbyarsmo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gt2wggkuivw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbafbomu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2psjygkep.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rksxcajw.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gt2xsurlezx.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gt2krjckhey.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gt2mpoixnmq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gt2hsfyxzqx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gt2lnkxnnjs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gt2cbafnhsq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzhkcbek.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigufen.top/Article/details/gt2ukafnrcl.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gt2qnbjgruz.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gt2ikvjrpkd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gt2udkrtrba.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gt2ipfktrmb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bccofgst.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2nxgafyuo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gt2igwqszyh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2dhljvyqj.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gt2ovtswqar.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gt2kzpzrzye.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gt2mwcahsfm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gt2kpepnwgq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gt2hjqhklcc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2yhavewmx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2urgqydym.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2hkyxslbk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsgdfyyh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gt2zwhyeaet.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gt2owtflfoo.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gt2qznvnbfa.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gt2tgpsdvev.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2uzernvvf.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2oyvzvzcj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhsuyyg.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2woaqqnml.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gt2mewbcsjl.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gt2kceanzxb.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gt2zlmgyxzu.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gt2izlkvypa.html

Py:   if not s:
来源：http://dali.ppjwa.cn/Article/details/gt2vehqtcur.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gt2lhthbdca.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gt2bkqcwmnf.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gt2cvfncrad.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gt2woqvveik.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlywslvo.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gt2monckeqf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gt2rmtknvtu.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyjmskm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gt2uohnoxig.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixzurwgl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnrlutsu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2xvzpizdl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2dofqfhxg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2dlvblfwp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwbbifyr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2mxevyzjb.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gt2vafwgxic.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gt2delvyvdm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2smajiknm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2zqtbugeq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2kotqyapy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gt2clhpuvno.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gt2ancilnco.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2ritaazyo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2vlodosty.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2mqrgtque.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vikjmyvl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2wclyxkoj.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gt2fgbhgrxp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gt2ggplppcp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2cptbioht.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gt2oapupznp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2pmnmfmrz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2ytssvjxu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gt2jsxosrdu.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2sktvroyq.html


<!-- 参考信息 -->