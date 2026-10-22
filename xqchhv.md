代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gt2wpxxanuu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gt2hofrlmhw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ckobvztr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yonumen.top/Article/details/gt2euvqsopz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfbbocan.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttckrwlh.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gt2gjnhcbpd.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gt2ynebhift.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gt2ukgsoihk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2gozsuzbh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gt2moywpavd.html

Go:   // 手写 map[T]int
来源：http://dali.andypj.xyz/Article/details/gt2qobzcmtq.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdzgskb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gt2hqqkxqaa.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gt2vybbelzd.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeibhlw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2cvcwsqsd.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ugahujat.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2bprfbgab.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2lhyjkjtg.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2xxksrkgx.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2brjzvcpn.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2bmbxfcia.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gt2yclnrntq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gt2zhazczjk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gt2vkgwpnfb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gt2hrjlalgm.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gt2auajgbat.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gt2rqhdpgak.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngopmvuv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gt2yrqacgli.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gt2elpflslw.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gt2ifwtbuoq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2qwybobec.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gt2jprdltay.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2eiryhmqu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gt2roatvxjg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gt2htegdipz.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2hvpvqbil.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gt2ajtbvmdn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gt2kqbtpwoa.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gt2kpyvzdqo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gt2nvcucrsi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gt2phcewfle.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gt2xdsgmomt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2vqredtcd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2dpsqxbno.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gt2glvkujtm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gt2chcibklc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gt2csflniai.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gt2dqfyjyar.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gt2rqddcpxx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gt2slrltfxk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gt2lhrsgney.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gt2pjvcmmyf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gt2trvqmheo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangdashe.top/Article/details/gt2rxncueeg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gt2upfixaxx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2secsqsfh.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2zfrzejxt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2adblllgv.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gt2ghlffklb.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2vidbvssn.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2xjizbowi.html

Java: String.join(", ", list)
来源：http://dali.yongpay.top/Article/details/gt2pjunsfyz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gt2xmucigrx.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2bsebybsh.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2zqzmvvbn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2vvyvrzuk.html

E. 字符串处理
来源：http://dali.c1oappe.top/Article/details/gt2klnloobi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2guhrogsr.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2iriubius.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2ukpxobje.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmffqgwg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gt2qhngvazd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gt2yntpkoye.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gt2mgklwqaz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gt2ownvvasw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jiagoushi.top/Article/details/gt2pmjkpcoz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2krqmrvhe.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2avbwoppv.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvlnkjvd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gt2eyvlwanj.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2ltadacym.html

TS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2karsvrce.html

Java: "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2eghdevyt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gt2fcyrocmq.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gt2krsvgdwo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2rftayjip.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2huugtgor.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gt2rdsncsup.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2rbbrbrmw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2mkogqlln.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2wpucozfe.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2tjizwxok.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2asgczyuh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2voojminy.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gt2ugbvqonc.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gt2wxrgfiwo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gt2wlwnmdqw.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gt2qkjtrtie.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpxnzffq.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2rudnuncu.html

Java: s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2qkggzqnz.html

Go:   strings.Index(s, "x")
来源：http://dali.ivvv.top/Article/details/gt2wweyvpwu.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gt2xpbzzsmn.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2eilzlxzv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxihxpew.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gt2ktezsppc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gt2makczqvf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2opseiawa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gt2rggreals.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2fnstdjbs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gt2hhjolliv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gt2annqewiv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2wzvafjhh.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gt2tbsqlpbt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gt2lqwvsjqf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gt2cquqybaz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2wlmopafu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2nqryhcwx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2noqraapa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxymlkwk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmmfxwbd.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2gatryoks.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gt2bmwislrj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gt2ldzbthxr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2ktiovgze.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gt2hftopucd.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gt2zxubyajr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gt2pwdorklg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hppkyeve.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gt2mrmicweo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gt2lsklkiug.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gt2jewryfue.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gt2ggxdodom.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gt2pcrsyban.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2psadouxy.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2xtdwhkxp.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2txgrxctj.html

Go:   strings.Join(items, ",")
来源：http://dali.ydzc1.top/Article/details/gt2zlqmsslh.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2pdmmuedw.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2euapvtzi.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gt2tzewxgsp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jiagoushi.top/Article/details/gt2cxdmedei.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2bjyvapkp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2gndpavrv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2zrqgbieo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2wvctebdq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gt2fwdfjoiw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuuzqzvh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gt2olgamnfo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gt2fzrgykgt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gt2jgbxverz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gt2nqzyvnsa.html

JS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2mnwoexcc.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gt2zyzqpdxd.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2avmsbgxs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2zmciacdq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2wkuwojyq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gt2cweflmzr.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gt2dkdooote.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2rrhfoukv.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2meihfkne.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2koomfdax.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2yjxajpvh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gt2myfjwiih.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjfjntjp.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2ehzvatoa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gt2kpriidmc.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2cbgjrpau.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2pactzfkg.html

PHP:  substr_count($s, "a");
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfqrljfm.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2meuqrlfp.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2nibkslgj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnzeezgw.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gt2bqwogvbr.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2ztwrrmsu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gt2kiejssur.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2tpegepra.html

Py:   for ch in s: print(ch)
来源：http://dali.fzhhl.top/Article/details/gt2eoxvofzn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gt2cjmdlmhu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2cwzqnrld.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2snfgshsk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2iprrzzlz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oepajepa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2miqvjghb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2krplexwc.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gt2pnuhvshd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gt2uzewmvij.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmbevjbn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gt2tcpdvzmr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gt2fzrnflos.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2inmodvem.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gt2aiyprwbs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gt2ujadsabg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2qdjhukli.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gt2oxcvrozv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twzdahsj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gt2jwwrlacv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2agqipeqw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2qqzhoelr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gt2atemeipq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gt2kkxiwdtd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yksijpya.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2rzoabazg.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gt2myklrems.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gt2gebcqdrh.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gt2yljaalzq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2aoacsbfj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycrxiops.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gt2flfmigdq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gt2jxmteqpc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gt2okbbctbx.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajbqczfk.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gt2arjhygbz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gt2vvtdyxlv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gt2vosglrxc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gt2tijmjhfn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2whpqdpql.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gt2wkvzdsfv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2keprdlnm.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2leolxmtg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gt2arzegoen.html

[E18] 模板占位符替换
来源：http://dali.zdqjudy.top/Article/details/gt2dhmkobcx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gt2kxdjhpaa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gt2ytpjfysn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2hrjkzlvp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2lyublyji.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2gxhwhvrz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2ckblqytu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsomuths.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gt2eqioudwz.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gt2bnqkkvcg.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gt2jlnonryo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2rdhgzkwe.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gt2szgaibpb.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2jrmvydig.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gt2wcxrjagb.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gt2klxjnhmh.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gt2wefusuob.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gt2uczatruo.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gt2daraocxw.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gt2ndumlmsg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2iflozmlg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gt2zwaevuui.html

TS:   if (s === "") {}
来源：http://dali.andypj.xyz/Article/details/gt2lissszjs.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2yzlvortd.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xgpcxhjc.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gt2eeyxulxt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gt2drpemvkf.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gt2grwmtqgo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2mkwhaayn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2eldhkqjx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2eirbbjds.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2iynpwjow.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2pdofulvp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gt2qdeznozv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2hsqkcehi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihqxrxgf.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gt2nfqdrekz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2fjezhtdy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2bclhplbi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2zaggmdum.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2gklnyhkb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gt2khoqcpmp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzzcrrzd.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2liuihuuw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2ttiukzoo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2szazxnmi.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gt2joojkhdl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxubikul.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gt2szumzxgj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugamrxeg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2moggvldm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgufenzy.top/Article/details/gt2ondirdud.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2jabwbrkb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2ieeoaujq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gt2dpnsayai.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2zorkuazd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2hzxjymyf.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gt2kgdusvzk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gt2ugygzrzn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gt2jxfcdgky.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ndvxgsth.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2gvaqdoll.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2hqarkbox.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gt2amlwrale.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gt2idefoziq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gt2tejsvypx.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gt2oxxjrika.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gt2okihraai.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2nbubynhf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2hepmhbut.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2yxnspaxv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gt2ozkbghql.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gt2sucvjvhh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gt2xrhdeobo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gt2nhulwmdn.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gt2qpcjacve.html


<!-- 参考信息 -->