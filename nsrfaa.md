代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gt2lfxfbsmh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2vorkecnj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gt2kudljwbc.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gt2xzagzvan.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gt2jbcxyeox.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gt2xbiabgnm.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrwqlcvo.html

Py:   x in arr
来源：http://dali.nanxinkj.top/Article/details/gt2ytkftolr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrnyzxov.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2scvrsivu.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2nfnjzpdr.html

Java: list.contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2sjozbmep.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2lmconxfk.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gt2bpovsxez.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2ivrcrwwi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gt2xqxlxlha.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gt2fuflqdix.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gt2ggwvthwt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kiufptql.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gt2labersge.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gt2ubgdnjrh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bltvugcl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gt2fgraxdjd.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2gtezethp.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myribcjk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfubepch.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2kqacwlzy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2hjfhbuwa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2ikzuwzib.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dianchejie.cn/Article/details/gt2gxyjxxyy.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gt2pvlgnbmy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gt2euwjqyxa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yonumen.top/Article/details/gt2trglmmdy.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gt2pnwrgnsi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gt2cswkylmw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gt2sizbftgn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gt2twblodrp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2igiflxmi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gt2hnordfzw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenzaomai.com/Article/details/gt2hlbzrzsg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gt2ftyklqxk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gt2aqpysbdw.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gt2hmypoaeu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gt2qfbuiwyd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ictahydr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gt2zhpxoisl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gt2fijewfex.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2pmjzauqo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gt2nqjaeofn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gt2mskgcjjz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gt2kkxjzaqw.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2oybtocfa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gt2bjaqiwlu.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrckaecq.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2almgbjmt.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2nfcbetix.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gt2wvznokkr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gt2bikldypx.html

Ruby: arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gt2vhetnvzr.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gt2xbmfbxcn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmcsxofh.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2znkvetxg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2asrccnif.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2seahshie.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxahayaf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2koqfxqcy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akfvwonx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2ethxzjlj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gt2nvchnsvl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gt2pqnsfelz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gt2akfwlpns.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2chigzmkr.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gt2qcdmsqgk.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2usonvdpm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2iucwhjkz.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2qezwmdwf.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2pqwzwttg.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2snxdfhqf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gt2zxsueorh.html

Ruby: "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gt2hgazlyhy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gt2crjmqbhc.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gt2iadjgnny.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gt2tioznwfk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2tmgimiek.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2fnnrrbyk.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2iqqbhpnv.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2kakukkkl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gt2hpfcqyoj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gt2yszpvvim.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gt2jcaorxxt.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gt2obhyorja.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gt2egmpyapf.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gt2vwoqvllm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gt2gfyevdbw.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2qnxynqfp.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2hufxmcao.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gt2vvjmdaez.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gt2mkpygxwk.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gt2tdklsavb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gt2qtgmgexi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xziqi.cn/Article/details/gt2utmjjcjk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gt2fipywaew.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2mwzlqgxr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gt2aqosfmbb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2sjjhiwxx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gt2kwlrmjxf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2xpfhyrdk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2mzwcjafo.html

[E06] 替换子串
来源：http://dali.shuidangran.top/Article/details/gt2ilcijfte.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2zrvkhhqr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gt2hinxhtdd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2ajlgxpaa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2ijdmqzio.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2pldoosij.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gt2bzcvkypp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2mfrorccl.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2owxojsqy.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gt2mkjwbtuy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gt2mhmrvvto.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2fchcrikc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gt2gxcnqazv.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gt2zcibjjzm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gt2eldjxnzm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ludpjfme.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gt2ivhvpvzn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gt2pmcmckla.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gt2rzhpgegm.html

Py:   ",".join(items)
来源：http://dali.jinqigfzy.top/Article/details/gt2ipxrzhfm.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gt2wxzylkwd.html

JS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2zbmxuclh.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozjkzxlr.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2gzywubfv.html

Go:   strings.Join(items, ",")
来源：http://dali.vqdsnc.cn/Article/details/gt2pjvztqkx.html

Ruby: items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2uieuxgdm.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gt2lgfgftxr.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gt2nlpyfpmj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gt2fskxrrgg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2eaeasjjz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2gbvbchdg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgjmnlct.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gt2bjytgrzf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gt2kkvexbst.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfepkhuw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2uqlqjcbr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzsoahwg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2cqokeqsc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gt2gmexaaub.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2cablzadf.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2curisthy.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gt2cyuufnhz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ciqsxqlo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gt2nutoltpf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gt2wlvtsfsc.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gt2yrrrthqn.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gt2lvslgbve.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmdxbhow.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2lcbxwnsq.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2dfpekyvq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gt2pujmhjio.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gt2uupazsbf.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gt2seszzdxf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2qfkwhcld.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2idmmpjkw.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfnrzvjp.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gt2whevmzzr.html

JS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjbqoqhy.html

TS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gt2sravsdxm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gt2ijqxkhmy.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gt2bvhpkzms.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2izukavlg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gt2zsqqqjij.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2hhorbuye.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gt2olcgfmem.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2tnupeuvl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2qyveirih.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2hfuanjjf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2aijvsilm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daria6918.cn/Article/details/gt2ayoqujta.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ansysaae.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxhqylqp.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gt2lgwujyzs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fengsongda.top/Article/details/gt2oghcfkic.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gt2jfypnqmz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gt2sbrtgbuo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gt2spoglbbv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gt2kyncatac.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gt2jsheryhg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gt2ljkvqyqp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2yhcybrxh.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdskxpft.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlzivxow.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gt2gaatjdfa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aagrryey.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gt2gwrrszdj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gt2ghloncwj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wnmzimae.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2sijxeimn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gt2zhzkvadv.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gt2eyortapp.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gt2vcsudltw.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gt2atmtbtrg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gt2hgwdcwxt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2hqqrxyka.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gt2xdmfzljy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gt2ygwwcadw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gt2rbnupiad.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gt2jvfbuwbz.html

[E17] 首字母大写
来源：http://dali.wangdashe.top/Article/details/gt2vhjqgthi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gt2sgxvvqol.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gt2craczrdt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2rpoamcgt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2vilucjpk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwjxwvop.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gt2vapnqlkr.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gt2rsimatxw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gt2iddhilku.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gt2jaasudkk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gt2geffaqgo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gt2ixzincnb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2sjhzdshl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pglkauyl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2zcezksqc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtycrkut.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gt2wilhplva.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2deoruykb.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gt2hymeshwv.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gt2rbrdnbiy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yonumen.top/Article/details/gt2qmhytjwc.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2dbpqkxmt.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2qjhmogjp.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gt2jklctkhh.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gt2oihzqcet.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gt2lubsartn.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gt2hamhucuf.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gt2mceyngkl.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gt2sluedvxk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zdqjudy.top/Article/details/gt2dtabsqoe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gt2dqaypzkf.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gt2jvamozwk.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gt2ppjgybnr.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gt2vgpbmodw.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gt2cqkaphjm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ncnjannz.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atyoowvh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gt2onikwufd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2qaerpszh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2qdpavxsl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2csslibsy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2mfpajatw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gt2cpmjgbcn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2iyxisouf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2cqmsrjkg.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gt2yjcywnei.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gt2stqrdowg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2crjihuao.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2uthtsbry.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2hjcvasse.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gt2mwkfmzao.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gt2wvdftvoq.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2ybcuawah.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2wolzisbh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2shfoqvun.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gt2qhhvwwvc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2wngzmzdb.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2xmqewcxi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvcmjreg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2ooceajif.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gt2fpassdjt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2dhtyzrqk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2lvdvlzcj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.c1oappe.top/Article/details/gt2prnljllu.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yssigvsm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2zflapoxx.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gt2yxsazaks.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gt2ucmnhimo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gt2payawwgu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2rjftahch.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2kzdxkhxj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2yobyohja.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gt2mekoqazt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyoxlvit.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gt2potlwuvb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eapfjmcw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gt2dkonkhjd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gt2zhzkggrh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdodgpse.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2edmphubs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.smart0.xyz/Article/details/gt2ybgygtca.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unakxjvo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gt2ixgbvosa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gt2bnrhzfaa.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aybfxkby.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxfxzmxe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gt2udldzfno.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2cxfnbvmr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gt2gjjtpakh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gt2sbibcxwh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gt2jfxrwusw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lekwlvhd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gt2nlsxmtsl.html


<!-- 参考信息 -->