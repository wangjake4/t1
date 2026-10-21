代发 wailian999

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gtbsrcnjrc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gthskpfjld.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gtccijecdm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtyfgoqtdu.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gtctreqmse.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gtpgwbpyds.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvdguzjco.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtestynyek.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtmpiupltk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlxodhmde.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gtqzykmvvd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gtamsuwpkv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtcxngyrlq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gtgvyqykbu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtnbtzolpy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblzmsunl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtqgvoovwr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gttxzlimae.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gtvfbkaoov.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gtlvlnyhqa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.vqdsnc.cn/Article/details/gtkjkoveya.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuanzx.com/Article/details/gtqvzllqge.html

JS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtntclxkfj.html

TS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtkupsebus.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtpbuerpna.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gtrqbqpeez.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gtmugdobxz.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gtsprknzmk.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gthklmwhey.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtjcsstbnp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gtfbaiswtq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhoulong.xyz/Article/details/gtklbvwkmg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gtjowwlafj.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtajdxogve.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gttthpzmsd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gtnenwhoqn.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gteijcjfco.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gtprjezeux.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gttdhgbmgf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtesidtkqq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258.top/Article/details/gtimabdecx.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gttuticbho.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gtjtmtxxpi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvmmqdmx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gtsktvyvku.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gtytpimtol.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtjzncgdyv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtcgycutlk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtijijglyh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtzjilrfjt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtigsmcfiw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gtzskfqjxl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtxyihlvnq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gttgwzopcf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtyharaguv.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtcmaatgcy.html

Py:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtygsueevz.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtsbsikupk.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtwgdhuisx.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtdfoqlmzw.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtwswywgfv.html

Go:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtnehlgauy.html

Ruby: arr.length; arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtwwowjqak.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtvjduvhtm.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gtrhakbstk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gtyyskougk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtpniusini.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtnjgtjikd.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtnraxsnkc.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtrxglohbn.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtpioaffmn.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gtysnrpebq.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtgwvafdaq.html

[D08] 合并两个数组
来源：http://dali.smart0.xyz/Article/details/gthlynytxv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtkhzuvofw.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gttunaodcc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gtkzuwqoio.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtotsmfwso.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gtrysjzmkm.html

Go:   append(a, b...)
来源：http://dali.wangdashe.top/Article/details/gtkyofzyos.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gtcijpleyt.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gtldaezlbx.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gtmabunbni.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtpzmqcjwy.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtlsswbnkd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gtghmybqoi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtqcteyrnp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpohsryk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtclwontal.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfryrbgyt.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gtirrtfhhx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtnqpvutem.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gtybczueow.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gtwbuxruss.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtqletayye.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtatsixkrn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gtkprjqjjk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gtmuojadsl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenjidiqi.icu/Article/details/gtekesyird.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gtqbnijyxj.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gtjguahnkh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gtewbvesbi.html

PHP:  array_reverse($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhagwhou.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gtpmwtaijg.html

TS:   [...arr].reverse();
来源：http://dali.dianchejie.cn/Article/details/gttsrhtufd.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gttmlqplxk.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gtingxkxhs.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gtsenlsnpg.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtwultvhvg.html

[D12] 查找元素下标
来源：http://dali.iojbl.cn/Article/details/gttdbgoani.html

Py:   arr.index(x);  x in arr
来源：http://dali.tanke756.top/Article/details/gtievkjxxp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gtyuikwqxp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtjpyofenm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtzvuawyzi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gtxhhxijjt.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtprrgqmpp.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtkkcxgmto.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gtyvpgpqfb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtwgcxqcyg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gttwaqfumg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gthnverdgq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtbkmnxryj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtcgecyidd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtexsflvaf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtjogrhvuo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gtrxqwqjlm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gtyxpvvxzr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gthahuarzx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtmklgfmfz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtbvaeocqe.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtjlvyvqiz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtsgeqpaps.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gticxdsopj.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtiuawcqee.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtemswqbjs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gtbgyugspn.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gtprxkdqdw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtvgdkkvfd.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtbkiwylnv.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gthzkbfgav.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtgthsqwbe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xziqi.cn/Article/details/gtycgvmydw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gtrontpdge.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gtftrydrgp.html

C#:   list.Distinct().ToList()
来源：http://dali.cqqwz.cn/Article/details/gtevvmoyse.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gtpfmhosoo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtantharbl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtgmckczlz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtwzosprge.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtzyijylop.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gtvhhqgnpl.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtilwmpysf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtwvobkeds.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gtiqazypqd.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gtrbfxfqcv.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtjrpmccpm.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gtpdwxrgqq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtkcxflemm.html

TS:   Math.max(...arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtjfbvumpr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gtquujfric.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtpfvmhb.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gtrqqgcnps.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtylllcval.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gttfckekbd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtmlokldcf.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gttekyclbx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtpbrgqakt.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtsswpapkt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtecdwnkqu.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gtygabwvxp.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtwjlwwbig.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtflbhhrjd.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gtpnsnixvi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gtjgqrikei.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigedabhm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dianchejie.cn/Article/details/gtbwcyyepj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtqgjhlvkx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gtcbrpgtpw.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtpsyjgfsu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtexfkumgs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghpnaxdr.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gtbymuneob.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gtqreejfhx.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gtglvztbmw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtbgqvmqlq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtaczdruuo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtrernqhud.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtuejkemmw.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtuhrehaws.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtozavjpdg.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtgsyvlllh.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gttzqiydiq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtxhaaetmg.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtbnqqczqc.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtrkxdwatr.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtrckphvpz.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyzoqbce.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gtsyhkzgzz.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtmapsuvaw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtphpxntui.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gttpglpooa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gtwcodxmml.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gtrtjqhyem.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gtsjysnbdt.html

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gttpcbpzcz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwipttsvd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gtuofcsnld.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gthjyajahi.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gtfwfilort.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gtaffgdpfu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtmocpiprr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtoixgjvid.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtqgykrgaz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gtelbclask.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtwkdzlacs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtrpqwrnjo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtbcrvemuy.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gthgzvcizb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtplcdvohe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtludezfzw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtvlesjcll.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtnefutoel.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtkyeiebfp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gtcdslthnd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtikwateot.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtnnlnbyxu.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gtxzxsfknr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtfaknguae.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gtzhyjrcjn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gtiggrvehb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gtavtnvrdq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtcpeydkhb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gtxmdlthql.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gtscqkslvv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nwbrower.top/Article/details/gtkqaefghj.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtqgirmokf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtlabyxcdb.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gtlgpldokq.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtrchpxfzy.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gteynaqong.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gthawmdnna.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gtjxnlzbyg.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtybhrkbmd.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtqfgrgckz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmzkkunih.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtzimsalyj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthrzskmak.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gtzgxwzhnd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtayuqgimk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gtqefbrduy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtylqcmito.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkripmcy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guannengcc.top/Article/details/gtojnjcjhr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcungoiwd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gogol.net.cn/Article/details/gtcwqeyycx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtilhynmto.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtfageekzu.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtorabcwxr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gtmriqxwqp.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtmclcdzwr.html

TS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtpxlkozdm.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtibmjjqoy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnxiangtu.top/Article/details/gthqjbpzku.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtgxuhjukq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gtwsvtfopn.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtxouubfug.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuckbxpz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtimnzhtod.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtfcxyfxio.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gteyzehocb.html

Java: s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtbfigogdk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gtavwoxtfw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gtvpxegcqq.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gtqzmqesiv.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gtojuejgia.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gtgomevqhh.html

PHP:  strpos($s, "x");
来源：http://dali.hfpthk.cn/Article/details/gttmbdyzcz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gteogiihrp.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtpzxgyejg.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtiicyrpxa.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtkdmcbisd.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtgfoovlib.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtnygsbhbt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gtsajlonsg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yangfankeji.com/Article/details/gtqheobecs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzddwvsof.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtxqowspmy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xylfe.cn/Article/details/gtctmijmxx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtxrxpnyek.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtnftoynmq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tian-w.cn/Article/details/gttrjtysyd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtjameyzlv.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtzqxkxnin.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtybnzfgnd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtnevtyeir.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtjqdstbcx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtbtiialoj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtwlojzpkl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygfiajfk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtriajepvo.html


<!-- 参考信息 -->