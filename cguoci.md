代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtcgkwvveg.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtbupdjpcc.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtkbnojcyj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtvdwlxfxh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gtlbvpfjyu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtrczuoxfr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gtwywgbdtz.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gtktmbfeju.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gtrlupplyx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gtltzupofp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwrydfbg.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gttdhsdxxn.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gtjsfiusaf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtmtphtkbm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtqnemdvlm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtnjmedrwf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtolxdwyov.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gtgqucdowz.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxqgdkqv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtetjgcfqh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gtgysirplz.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtadtdqlkc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.redwolf501.top/Article/details/gtylrdjdqh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gtlwuaacxo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gtzsbyghkh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtkefpblxp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gtluzemabr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.snrcjt.cn/Article/details/gtojiatwmt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gtybbgxzcu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gtybtpzmqm.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gtdjqefkpe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtslmbpkqx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtmvavokst.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gtobinatyj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gtibjsrnhe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtolukrezd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gttcpsjoks.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gtecpfhjcr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtsihafhhm.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gteakwiews.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtvsdoiukw.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtlqudxvkf.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtbyxqwjck.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gthwulgfci.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtcebinbir.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtetbhdtjd.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtnnoceomv.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtfvewnlkm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvciglivf.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gthsfnksof.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfmzulpds.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtbyqtrzvh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gtvlpnnser.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtdlgljwkw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzvhpopt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtmddsqoac.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gtubkgiecb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtblstkzuy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gtftafhlye.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gthdwtlxmh.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtwlzdxjgy.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtbfgptulq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.c1oappe.top/Article/details/gtpbqjziow.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtxskqeeql.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtyjslxqsw.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtbfkemwbs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gtosghsdan.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtmefnbhxo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dianchejie.cn/Article/details/gttvfxhdpy.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtflmlaqun.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtmoizynuu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtckkrgoaa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtybicyagb.html

TS:   s.slice(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtyuawibbr.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtmabwswmj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtyqdgeafa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnqzz.top/Article/details/gtryflhwsx.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtbasmscbc.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gtlangxswk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtqwrbawav.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gtdtkfbppi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gtcheofkec.html

TS:   s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtfjfxlzen.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtapofkowa.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtxtsstjds.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtpcrhrdvx.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtarylceae.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gtvpkvdtzk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gtfaztjoie.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gtqytddbbg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtoqidfteq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtzudwlqsu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtslshyemr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gtgjyngiua.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtxzqldedr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtpthqlqni.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtaxthemdx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtswcwguwt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gtzwwekmds.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtfrkkpzsy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gthqwhfizt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtcihmqufb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtzokxsvgd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtrpbawvmn.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtkgyvamvb.html

[E07] 按分隔符拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgoouzme.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gtprjblbpf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtogrfrbgk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gtjqhqbgzg.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gtitevmxmf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtirkqtulu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtqmmzdtgv.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtjfantzdx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gtnpyfdhar.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gtvupturdf.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gtagvvuion.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtxutdjchn.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtuhfkxbij.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtwquznspm.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gttzixqmip.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtzuukwgjd.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtnlqgdpou.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtayiklkdw.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gtlxuhrnvj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpykrcbeg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gtqlolegow.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtlozgejqs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtqiojnfbr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjacwfgac.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtkpftqdre.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gtugjcujlx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcglasib.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtpyevudyt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gthidruqxq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gtdzrkvkli.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtgkxgjkfl.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtigtgjtzb.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtaradrdds.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtjuhrggyh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtbnpdlsbb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jiagoushi.top/Article/details/gtnlegnths.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gtxbjbnbwi.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gttrqivrls.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gtgajxshyd.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjdjifng.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtvbfppjzp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gthiatpfqk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtncjgxbdo.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gtclxzstkq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtjfdtlcow.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gtojxqncjp.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtwfsqffnv.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gtwffsktld.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtpaatcjic.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gttnppezkn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj202588.top/Article/details/gtqucdpdtw.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gtbmbnoqdf.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtdckoozfo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtbxirneug.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtuuoxspnz.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gtqskjhtep.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtbadlcyas.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtkszptsps.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtjjeuvghd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmzxziha.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gtuphdurxf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zdqjudy.top/Article/details/gtxvpcwysb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gtkuzziwcs.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtmifavzsv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtpvqzdrcl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yvedp.cn/Article/details/gtnotznpjb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gttdgmbdvb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gtxijuuleb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.andypj.xyz/Article/details/gtrnbpwblb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtzmikjduv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtrooaascm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtwrckjago.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gtypsrneuv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gtkkyatmzn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gtxpichbds.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gthqnokcnb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gtwzaktenu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gtsomzdlcd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiokxvotp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtozjslhzs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtizrubzrp.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtwjbnngqt.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmijzhcd.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtxghtywki.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtaevlkptm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtoaulsbdm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtwjapwkam.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtynoipwjc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtlikyvsaj.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gtfruhdixd.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtqklyvcdp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtemgcuuwu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gtkymzbhet.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtdmfhfreu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtfujrfxzw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtodoqcofw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gtgefxrrvd.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gtgkuvppam.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtwgdjnkjq.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gtbboulnqi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtivibsini.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtgysofnjk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtzwqaettw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtkducrzpo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gttapjkgch.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtvkipfage.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtcdbdqegr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtjocbolcp.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtsqcjlwqu.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gthtuzrhzu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gtfbqjijjz.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtggvhjzmd.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtxicidrnm.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gtzyvvovgy.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtjkxsyaqo.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtkmesshet.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gtdmfclxbg.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gtreyjgslg.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gtjkuelxqi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtjpkckaxb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtrakugwjv.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gtczrmuxnt.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtfxzknyso.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gtrxxzycgx.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gtzlfoxcyz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxlyocqb.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtvivtczkp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtaavkvzmu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtsqemlmod.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtxlcqxilt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtdxkhfpfe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtpkcvyryg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudzwauwt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtmjppjpol.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtzcevifgy.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfhpzjoq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtflqhmghn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtzzdgwigz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtiydgwpaz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtqutdxmvg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gtesonztuq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtsrfcibsl.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtndvximfc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtwtcqhrbh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtyejatdmj.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtlbxtpyvb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwftarbdd.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtywbdqsec.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gtgdpfezkr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtoycfrqsz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gtkmshsysf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtrxqedzsh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gthxxuqequ.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gtrfoeacpr.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtodzrrpdg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvibfacwm.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtmojikjwq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtbquxyxbs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtroygxrpd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtvhldnedk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtxzzzsabg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtundpltyn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtueiovpah.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtuqkdolve.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtugxieogi.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtzwdkzazj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtojjmpnpa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtkzvoaylz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gttqlvejjv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtozuampeu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtgjmxpzan.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gtrfunbltd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtamiqkwyc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtazxjtbrl.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtbwaeuxuy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gtfyhtrtkf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gttkcvkxfl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtswfjhzuc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtklyemksa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gtfefqpqqg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gtgjalgetl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gtslhnrjpd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtzahqplgk.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtutdsegwk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gtzibqtkqs.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtiiuzhpml.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtxvoqfhsl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtaoufaaqq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtqnznkicw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtbmowmfrl.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtduovswgo.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtblmwqruc.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gtnhetogua.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gterumaxgy.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gttajaoenz.html


<!-- 参考信息 -->