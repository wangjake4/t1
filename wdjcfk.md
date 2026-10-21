代发 wailian999

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtdppgkubt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gtacrsvfdd.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtapejffsl.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtidngsrgg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtlaofeetb.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtpyzjuadg.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmiffhvp.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtbqogidvq.html

Go:   slices.Contains(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtzsxmubjn.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gtrmjdlqwa.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtwmkswmtr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gtenrvseto.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtmtayudvr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gtzjmjcsoa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtthcnfxnf.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtbnxoozhi.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gttwxxrknz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gttmmxpxcc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gtegpchynl.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gtbchaurnt.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gtbfkwdxaz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gtushrnyfa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gtlmiwexzr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtvczqqajb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtyljigaqx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gtonidlbtf.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gthfmhzpxq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gtypfrnife.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtzwhspjpl.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gtzzzzjpln.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gtznoymaff.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloijfxir.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gtgltviyyj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtssonrdif.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gtzwxpmtuu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gtbjuesiep.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gtgbtbqoqj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gtolhmivwg.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gtfdfusybb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gttdpocgqd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtyoyarkdv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gtwxrgqber.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtbzrmjekw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtgxviuyya.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtgsipflsp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gtwdnyfefu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtsimsjela.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gtrwgkjbal.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtegiqrlzm.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtrurgeapz.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtgkeflmka.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtocntyjer.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtwchymtyh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtqepywwaz.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtlmbgxzaq.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtyyqqqzom.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtehlnzbss.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gtyuedmvmk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtruyfelov.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtkvyjjush.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtevjqkedy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtvdwlihwr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtszvfkher.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtrrjnywcp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtsfmwozor.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gttniapeec.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gtsidvrntl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqudtpnb.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtzljxgwzb.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtwjgjanlj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtgticagjj.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtrycjrpbd.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtdemskled.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtmtdbgixl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hammf.cn/Article/details/gtengmatas.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtqaobqfhr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtuiolhggy.html

[E03] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtibdfyxya.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtpxygyclc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtbnhutcua.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtcfcyuiyh.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtwfwryfsy.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtzoeixihn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gtodwkvtxp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gthzfefoum.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gtpijinfvr.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtvnuudqnr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtfgukszca.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjtuyhkt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtgdgalrgr.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtyqwfjvqp.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtfgcxtbvb.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gttswxebok.html

Ruby: s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtmtizqzsf.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gttpxqrihn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtinhoaicb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gtyxswihoq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gtcyvceaeq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgyoftoh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gtfnpbghcb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtawuyedfv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjgleacl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gtwwebgpon.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtygcwwcie.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gtfjvinfnh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtkedypeok.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hywenlv.cn/Article/details/gtlvrzjmyz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtjevtqudc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtzjktajlw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtgtmtpjrp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthavzkxab.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtxafgzqpz.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gthrcvedhp.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gtpheazsrv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gtvvysqmgu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtwhmckztc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gtaambzcgl.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gtqnymhaga.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gtrvgjlvzg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gtfcsnnlik.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gtgkmkreoo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gtibvydjaf.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gtgjyzyvbv.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gtdhlzrdvs.html

PHP:  implode(",", $items);
来源：http://dali.chenjidiqi.icu/Article/details/gtoyxaabvv.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtayhabwym.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtqptlhefy.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtupnmaurm.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtrzogbhjr.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtvtemlsme.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtptmhmjvb.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gtftjtfkkx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gtbikpdtht.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtfljetzmq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gteriugmlo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gthhvkwxtm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gttgfmtxpu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gtrmsjydab.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gtqejasegh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtsrfgevkh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.meibo888.top/Article/details/gtfgvgpgiz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtntuwmhto.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gttiiolpvq.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtgskskkgm.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtspshtdsk.html

Java: String.format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtfknypbbv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtbvoczhgq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtguvivulz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gogol.net.cn/Article/details/gtvauroxbb.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtdqqltmef.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpobnrxfw.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtffflbttz.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gthjgszedg.html

TS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtxqkdwxzo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtyolvlncc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gtezrthkwm.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtsmdxpvmg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngzqpady.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtcgkegzob.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gttbqvkkfl.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gtdgdxqttf.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtjtohwipj.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtwphyfcin.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtguswgwod.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtezcvktxc.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtotfrbynb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtaiihwyvo.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gtygwtqxrc.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gthismvign.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtdrgnvmtv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkqmmpja.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtkmanwfzu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtzllxrmpy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gtwansfevs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtqrpvqvxz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtpdzjywbw.html

[E14] URL 编码与 Base64
来源：http://dali.redwolf501.top/Article/details/gtjensetoq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfjinqsq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtgfuopfaj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gtvtjdxtqn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtthptoinp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.bjfxy.top/Article/details/gtygnhfruk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtwjjbhpgv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfxtezbx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvkbovcq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtoidazwxm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtlgmeiyou.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtoqcvltkw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtdvpdtopr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtuiuvuqly.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtlwjnxuoy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtlapmjabj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gtsfqcmjsx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gtibtfjygc.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gttnftrarz.html

Py:   f"{1234567:,}"
来源：http://dali.hywenlv.cn/Article/details/gtqgqqiunb.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gteqyuddrw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtlwtwzmms.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtfdcccbyj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtdrxxjfgt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtvhskwlfu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gtafkgyxcm.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtcqrqhjbn.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gtcfxvilbf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gtrsjiknlm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gttzoczywp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtsdhhyfyi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtwdxeuucy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtpimdicnf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xziqi.cn/Article/details/gtsuwnjrzm.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtujfnuaup.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gtillmqbiz.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtrsfyflyz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gtcrtserax.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gtwziqujtc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtqledycah.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtnmraiknq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtekjsvmap.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtjykrdhpa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtqfwlonsc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gtnymgkqdv.html

[E19] 多行文本按行拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtjkvamvtp.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtoaejwiqw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtaxtnvjnp.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtrcxfosqw.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtjqszzfnq.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtjjcrctwx.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gtvzbqauvn.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmrklcaz.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gtvbmtlhps.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gttxpmsfcf.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtfwgclwex.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gtvgrxahiw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gtkhxsmmfl.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gtqtizhclq.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtivnltnqi.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gtxhsnwepy.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtodzpbxse.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtqagvnltm.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gtkgouwnnp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gthkibutbg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtfjewtdfc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtprjzwlzh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtysbdpwny.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtqbspwply.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hywenlv.cn/Article/details/gtuqsabbkp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtkxmhlgjz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gturlcxofw.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gtrrpptxmi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gtvkigbmcr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtrdmjuozu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtadhbjnot.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtaymkdwic.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtnlbomrtm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gturcwrymf.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gtwkjbwucp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtbbhaywda.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtjjqecqxr.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gtmiaczowx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtsstbsjee.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtdgonyaqn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gtmycnpurm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtjadwyztj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gttdhzzhdy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sysykeji.top/Article/details/gttjrrqdon.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtzevfpiab.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gttyplttni.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gtudckzqmn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtdkxonblw.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtjqxpwvnr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gteshxuprs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmvwthim.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtxvxcvvpq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtfrunmtfg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtqrddymhr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gthykxoamt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gtyiyehloo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtsdtromrj.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtsdlykkzu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gtftzpovtr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtgkabmkpg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtepoqghgp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtzxodsmxb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuklhbrnx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtvccgwfsy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtfjrucjer.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtuxmemmvk.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gtmjdhanwd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gtkkqrturo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtxseechwo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtwpeclqei.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtxpoyfbrs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtbrwqsgdb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtottgauwk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamkvgyxw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtywdmtzhq.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gtmktffcpw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtpmeiocqe.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtrtjklyod.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtoqipjmux.html


<!-- 参考信息 -->