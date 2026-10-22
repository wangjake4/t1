代发 wailian999

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gtrpeofqdz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gtwhszvqny.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gtpkrtivkj.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtgjfxtlek.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtdigfhjag.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gthcmfymix.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtimnnkdbm.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gttcpluouu.html

Go:   slices.Contains(arr, x)
来源：http://dali.xziqi.cn/Article/details/gttdseomyo.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gtzxdefeat.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtqjcxflza.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gtfssuknmm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtwvtqkyme.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtgfaictco.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gtrmqjbtmu.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtikbjjnrx.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gtwusvoios.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtersvaupy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gtkndueltr.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gtqoltammr.html

[D23] reduce 累积计算
来源：http://dali.hnxiangtu.top/Article/details/gtnyasmfxx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbikayphk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtdlyiejkt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhvnhgws.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtusgvqdyo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtdwpopgyy.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtvrcgiitt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtgbqfgzaq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gtjhuipmmm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gtcrsbhghw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gtsgmnjbsb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gtqakwkire.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtffzzmnjs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtwuznrsoj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aibaodan.cn/Article/details/gtiubtjggp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtuwhaevkx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gtqhgzxqkt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gtfgwopgmf.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gthxgcpwcq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gtmhmaghjg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aibaodan.cn/Article/details/gtztgtwyuu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gtspzxvsfv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gtekqjdrti.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcfdincq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtxwnfuqkp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gtgrqhsxsw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtuxuocgjg.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gtlstdirhk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtairdcstn.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gthgcfhpvf.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtqsuuolfw.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtycbvxyvc.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtboofdpac.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gtrkbddmeu.html

Ruby: arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtijlznftl.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtzdpztqbh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbuiufqyc.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gtnixzhxtf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtheezdfxh.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gttojcudni.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gtzftrwtmo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtzjyiohut.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtkcltmcfs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gteiepqgyl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gtfakgrqod.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gthhtykkjf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gttyikghmp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtzqjaczjp.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gtvfmaczdt.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtastrywgx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmroyzsi.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtwwxsqlei.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmajrflav.html

Java: "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtwjpuqdba.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteudzvxcr.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsrzqier.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gtnhckakgb.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtlxuibqaz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtiecnynsz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtfnihxyqd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtytkdolrc.html

TS:   s.slice(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtepxiixgt.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gthfmgqhqt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtbhdkxgdx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guannengcc.top/Article/details/gtuaakuodx.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gtdicsytjk.html

[E04] 查找子串位置
来源：http://dali.hnqzz.top/Article/details/gtfegrkivn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtycmhcodd.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtgrtyyino.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxzzagdm.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtvfrhotpj.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtsrfmkafr.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gtolhbeqce.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtcmfwsmnf.html

C#:   s.IndexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtqasecxrf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gtpholepkp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gtpcvxmxoy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnevryeo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtfwazlllj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gtsxmjyqds.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtzxfpisxt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gtutzthxth.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtcguvmhty.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtugzaqpyv.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gtaesgxtwk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtgefimcqx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtgamziujy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtfjierqqf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtiwiixlgk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtjyvpfkxr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtvinbrzyg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtlmkrnvvx.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gthzdhusgm.html

[E07] 按分隔符拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtrgsivfok.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnxozjlk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtuxligpin.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtklkktkyn.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gtfrxrfwei.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtyhthwjlk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.vqdsnc.cn/Article/details/gtsogplqai.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtsrvxlzfi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gtmhskxrmi.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gtlvfyjhao.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gtlskfqibv.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gtmrlbsjsn.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gthwzsrzoy.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtbkjyaqzx.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtsfrrtfrf.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtigmihphj.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtvnbrghnp.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtnvepxozw.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gtrotzbbzb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gtwgjbhzsu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gtagfbufzj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtxrbdlkfx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtqfvbojwq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtkiyyknxc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gtllvztpeh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtkkrbbmwm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtghooyrav.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtwbeknisz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtgznaiekk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlggjblr.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtekugodto.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtekuqqrib.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtzwytxbys.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtjrljkvno.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtxinbqjdv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtbwvtsues.html

[E11] 反转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtxejocefu.html

Py:   s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyndzrsd.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtvvhtcnet.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtyrjvzerv.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtabaqkgku.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtocbiqfxh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtlmeyseay.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gtqiujvyep.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtlsaqdzhd.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtighirghs.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtdulchfem.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gtkvlhyhoa.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtluludwgk.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpitjkxnz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gtujmmqmsk.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gtazzuzuci.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gtienyzqvs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gtwejtzsrq.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gtcsxzmxzr.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gtspgaxflv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gtquekdvrf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gthmavppfj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtekqptzcj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gtdcmudcou.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtaqoxypeq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gtigcpxlap.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtqszumfcv.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtfyacjkdt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gtzesscppx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtdclvrxot.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gtngcpxbgf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gtsltkdnxs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuphlzai.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gtawkoqwhf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gttifwofsq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtlygcfmyj.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gtryxtodia.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtwomvlmkx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtcfxtctyt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlemklhzm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gtiuexrjnd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gtjujgyaeg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtzfmzqhoi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gtioidzzlj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gtcfxeaccw.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtcaemdsxo.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtghhuaaiy.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gtwjxkezjq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtkpgcxgjk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtiatlvkiu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gtxfgaqhgi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gtllsegpll.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.andypj.xyz/Article/details/gtdurspqwa.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtrbsejdnh.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtaqodmmzz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtzfnuhhzj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gttwcqdcsd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gttsissbxe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtwodhriwk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gtumklwwbv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gttzvanlhk.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtekigiqdl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtppsifwtr.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtilwwzbyc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtjluuvjej.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtolwoalit.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtcmtcansd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtrcjirwij.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtcsopybwh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtxpvssyoo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtfatxvyli.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gteghglcut.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtxnreoojy.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtwzittqrs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtxsnyitgj.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtxfwzpwrl.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gthkfqxani.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gtoujfrhmv.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtniqwtjqj.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gtrveixdfo.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gtelsiitev.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gtywbjbuaf.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gtemofdctc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtjisgzmoy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gtvpotwuqp.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gtjsglprjt.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtpucdohed.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtqkjfmniz.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtiaovxusg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcqefbhrl.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gtlvjxrlre.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gtrmmzlhto.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtwedwljtp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtfuroxotv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtwsrhqaba.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtyezpoxjk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtkqcsbmjt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtmcxamlqm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtfijsfyir.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gtaquiwbzm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gttjhjribc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtpybrgaqq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtppsojoyn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtriiimnvm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtnwnbwmcu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtwiicjafo.html

Ruby: s.bytesize;  s.length
来源：http://dali.iojbl.cn/Article/details/gtcxcluwhl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtxykmqucu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvhkwbwxw.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gtvbkkoxkw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyaophbht.html

[F01] 读取整个文件
来源：http://dali.sxryk.cn/Article/details/gtdktnosao.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtpkjatqqg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtescpgxok.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gtxyknfkre.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtujlpyjiu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtedizgzcv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gttgdvjawq.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtngzfekcs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gttwqicags.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gtaroxwlab.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtsvvtwkxp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtamhkxnam.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtaorixnbu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtelsayhwd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gteylddsda.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtjbiikorl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gteousjiay.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtszzhvtbc.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtjhvgriye.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtkfkxbnoj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtmsagrqol.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtoaewmbdj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtbqbzsmsx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcwokjba.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gtwongmlnr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtllmmksjk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtucnegtqu.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gtradvyyhm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtqontaswg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gtpjuajamw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtvcxzmars.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtgjcewjzq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtcisstgpx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtsdiqciva.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gtlebjettq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtfrqbdgjr.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gtanlhmlcs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gtaivleqce.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtuojkjogo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtrganxvau.html


<!-- 参考信息 -->