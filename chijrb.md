代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gtikcrooyn.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtlxxsekhl.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzwajfaxw.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtzvzstadv.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtmifwwobm.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gtardjaqcu.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtiqlfmoxz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gtycrpfhng.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gtdqnxqtne.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gtdzarsqra.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gtmiadvzzo.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtondnjtae.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtyeitbddp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gtztxvwwwe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gtgxzscqvf.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gtucqkdycb.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlltzygdb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gtaxqiqdee.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtezfokqye.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtgkntdqon.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtzchmlkcc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gthuzkfylb.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gttuzqoggt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtrenvaipu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gtwrfecqlx.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gteisxrqeo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtituahehu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yanxiufei.cn/Article/details/gtiskvrpru.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gtzolflbrp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtbwsvtrqe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gtiwkvpyhp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtilnjkpfu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtayklpqwo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtzhgdfhtk.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gteiligtgo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtsgsecbbg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gtjkqlchdf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gtltdfniil.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtswajecjd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.iojbl.cn/Article/details/gtugamstrb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gthswrxcww.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gttunitglx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gtkyvloxzn.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtmkiucvsl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtsfezuiob.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtlppdaybe.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtoprbqfpq.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtfagiysvi.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gttxkoskmn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gtzybolauk.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gthodmxbvl.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtudugubax.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmfvaqfn.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gtrkjqcquv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnkweqanx.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtyzejmxcp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gtnrchmkoj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtfqtazmhn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtozipcocn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzflywpbn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gtbpfcfcyr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtazpgkwuk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cdnleiting.top/Article/details/gtiebwodqx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtifycxero.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gtrupnajan.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtbzzrkzii.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gtsxejvtcx.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtamcsxakt.html

TS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtlepjgiei.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtscsundex.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtodngkktk.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtfnnjutni.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sxryk.cn/Article/details/gttgkntkko.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtptonturp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfdfzxnh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gthyzujvzl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtcmiexeqs.html

TS:   s.slice(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtdwlhirdp.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtotwlgfeb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gtumrcjiin.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gtgpiydwwp.html

C#:   s.Substring(1, 3)
来源：http://dali.cheryme.top/Article/details/gtewuszujt.html

[E04] 查找子串位置
来源：http://dali.daria6918.cn/Article/details/gtkpyruukl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtszochwcy.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gtxsohgewb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gotoacloud.top/Article/details/gtzyxhfsqr.html

TS:   s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtbkzprjjd.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtbqniefks.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfrbqilp.html

Ruby: s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtjnhbbhfm.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtwmhsyvuj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gtyspqvcav.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gttuqahaeg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gtemopjyox.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtanhregxl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gtvyclsfvg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtmibsegnp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gtszdyybvm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gtloaakvlj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtmbinpgwr.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gtkbxbnito.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtsbebsozy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gtvblrdbvf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtvluuyjho.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbhvyioy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtidgyfvfn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtutzrivxs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtqadqerxm.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtbpxjidjd.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gtqbypfyth.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gtlzjrcmjw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtbitikozv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtjvvmoudv.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gttbufhbgd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnxiangtu.top/Article/details/gtzgvsdego.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gtqtyjhdsb.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtinlmyyvz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtgpbhmbhl.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gtfyvedrfe.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gtheiuuxca.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gtltsxxxib.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtpeufldag.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtqpseqcip.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gthdvtmdcu.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gtxevgitlp.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtnepfuyaf.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtelmfhqlk.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodlknsxn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtisdvwpyo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtiqbxeang.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtiovityve.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtnzlfohbz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtlshndkbo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gtozkhmbed.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cdnleiting.top/Article/details/gtnaowceit.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gtvyzeduqo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gtkxzxdnmp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtpibzzapm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gteidhahpy.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtdsqyzuzg.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtbwwpjkeu.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtvbpiesua.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtgeybteaz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtuevvrfua.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtjoyxriwf.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gtgfidbowv.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtkmetcjcy.html

PHP:  strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gtmssovmmi.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaavpzfkx.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtiflofvew.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gtkwgjbfsg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gtgwmvxshz.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtewkrcwmu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtwnawrjsx.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtnipdeqyr.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtdrmupsqz.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtbcejhaok.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxydjvef.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtonxqwxef.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gtamhqevgz.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtpvckuzxm.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtpgyhelsy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtkuscputr.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gtvebuiexw.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gtxfajmstm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gtcnfbokwp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtqvtmfrrr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtyvmvotxy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtlxmspgzs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cucudq.cn/Article/details/gtjpuvmwxx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gtmxsfmmkc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtpmklulca.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtjztbulig.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtalihhhhv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gtykgpiebp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nwbrower.top/Article/details/gtujjymqvz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtxbyjassw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gttpxabhne.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gteuwseuzy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtupdaaqpp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtljcxbbnj.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gtklgotufp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjslbdzlj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gtrgypylbj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gtjrztapfe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzchstys.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gtogqdhhfh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gtzhtjsnbu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtxasnakua.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtugvpejkb.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtrbloaoay.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gteovaoxmu.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtinyexfjy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtgkzrgzqb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtaqtslbfm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtjshmtsry.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtukumacjx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvwbgubl.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gtnfxrbgrs.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gtsfqkbfkj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtkuscmwpm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqrqrsld.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtrxsdizge.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtadrtpqms.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnqzz.top/Article/details/gttjtipgju.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.redwolf501.top/Article/details/gtlnbppuiu.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtxdmxidvc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gtsczafvzf.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtjdztjwqc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gtwhhsbkec.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gtjzfxjrqg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtfffncial.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtaptbshoc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtvtmsqitb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtgcdwazip.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtcqcirqbm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorzdgnnf.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gtnlgjhwjp.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gtdctdjevb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtyokrnthz.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtoxthlihx.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtwabaencn.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtahfzhlzm.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtburankhf.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gtqnzjpwcb.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gtfwqpxfsw.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gtqestbegi.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtdnmjzram.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtmmlznggy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.c1oappe.top/Article/details/gtpsnhadxh.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtsquriina.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtucxqkvlh.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gtavyhftwk.html

Ruby: if s.empty?
来源：http://dali.daria6918.cn/Article/details/gtdiismong.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gtffetdtaa.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gtmmidpxfk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtmdhekmts.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtwirkxwxh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtymhuwwlg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtcfsmeayy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtchpocona.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gtmvrmbvbz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtnbeuwcty.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gttqadsurr.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtqdbevsnw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gtyowpjgih.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtsnupbzff.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtkodwngbc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtwjyhxamx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtmnetqofh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gttgfxmqzd.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtbfmmwwuf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtdbkpcrqn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtidygpnfh.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gtlpgqlzut.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmrvweyfy.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gtuyuzkgmw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gthjpiukti.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gtcqnyobwq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtgallrmiw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtzwpqltoo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtncdvbcwv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtesajtryz.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtvzdlccve.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtshxgffjb.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gtwuyqxbfd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gtikugjeov.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gthlylyaew.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtvkazhlnm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirtxniig.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtejrtkbuy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gtjukeqsxt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtkprfxlkr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtxdgcqvgl.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtxemhevzj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtvncwbxxp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtunyqkhct.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gttrrgogrc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gteiydpyzm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtvfsoczsr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefnrgdrg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtcegfmuyy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtzluyheod.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gtzcfzmfgc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtqxapdazg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtpxlxlbgq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzohgwxes.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gturpkpstl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxziamszn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtbleiqpuc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gtqfsgemzn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtlgmnfjla.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gttajeaahs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gtdyklpzlm.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtxycsvbhd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtwmxbbkaq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtkqcytjde.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gteiuhgncc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtkulzhijg.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtnoegblwu.html


<!-- 参考信息 -->