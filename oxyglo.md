代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gtczdcpcyh.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gtupwsayrd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gtovmbsvmk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gtaguiggpd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtqfpqoyvx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlflzktwy.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtuwbhbuwv.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtfwiptqxu.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gtztafjmco.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gtvbiygjey.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtsuenkfwf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtyrjunaud.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gtgpuhnxsp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtsmcdzksl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gtjqruiauk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gtkhhzhmuh.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtribkdtbb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gttnlxdfhd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gtoiwuendv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtltwutadb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtuxaxbxpg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtkvngqeyu.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtmfuxogvc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gtyoddvjgd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtnxlalisd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gtjoxdwkog.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtsnvhytpt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gtcmwqbpbb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexikuobm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gtcmjyzjvl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gtjdqparzz.html

[D02] 追加元素到末尾
来源：http://dali.aizwys.cn/Article/details/gtjyulvsgk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gtdqooeaio.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtvokdhxww.html

JS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtajpmuocb.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtkjrmzxce.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyullkvw.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtmossezgb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigfzy.top/Article/details/gtkgumyvgs.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofhpbgxj.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gtsttwtrmq.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtteskyqbu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gthkvavssi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gteicvlueo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.9152youxi.cn/Article/details/gthakyejxl.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtnatavlbk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gtkdbnbvha.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gtyjevbeco.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtlgsvjomq.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtxotpbxyx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pycfn.com/Article/details/gtymcgyxrh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zycfv.cn/Article/details/gtqzfzzewx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gtdabqmpny.html

TS:   arr.splice(0, 1);
来源：http://dali.hnxiangtu.top/Article/details/gtbfmzwbmh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtplqdoipf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gtmamtfjgy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtldahgmko.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gtsafwvtlb.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gthjjngvfz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtczetvtjv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtogxgusju.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtrjdsqaws.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gttjqpyowx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gtqjdjvjgv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtpdwhyjbq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtzzoiwzvq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtjebnchee.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtfpzphjia.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gtbkzkletz.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtroblbcbw.html

JS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtepbuztre.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtlqpbtbqs.html

Java: list.size();
来源：http://dali.tanke756.top/Article/details/gtcqiswocz.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtlulslnup.html

Ruby: arr.length; arr.size
来源：http://dali.nwbrower.top/Article/details/gtjxwgbuzy.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gthhitisri.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gtqyozrpgx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtfijncfwg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shuidangran.top/Article/details/gtngjoctzg.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gttvzaqohn.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtrebclwzk.html

Java: list.subList(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtasajffys.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtfwkmngmk.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gtxrulgtig.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gtghijpubp.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gtsuwxleus.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gtdvvqwnxy.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gtdqhwnati.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gtxwbpdhst.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gtbuofprro.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtlnuodvwk.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gtmtzkqwou.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtxfakabad.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtnzvwgzst.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkwvbcok.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtycniqhkv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gteptywlzn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gtsiankuut.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gtxjwykgjl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gtkkbcijki.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtawdqdzut.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtfnejkavs.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtkorbnplr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gtdeijhduh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gtezrgjtce.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtlzeqvvsc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtzhqnwwab.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyquhauzm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenjidiqi.icu/Article/details/gtxbbclheo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gotoacloud.top/Article/details/gtllulbhwp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtglcfxkzx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtuyikosbh.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gtcpceuasu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gtgipdhvgd.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gtbdylqtzt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtcfakmqdb.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gthdutguaz.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gtahkwgfhv.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbdjggcue.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtcggwsatx.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtkbvqfsto.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtyxsskqxx.html

Py:   arr.index(x);  x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtfudociyu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gtcqgogdbe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswijdlls.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtugtgjssn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gtxtiaffic.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtxwmfqwdb.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gtfdlyadrw.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtowknndol.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtleoqpbwv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gtwjtgkmmh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gtktyddpmd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtvdonfvis.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtkyusymsb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gtehypugao.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gtmbrzrbye.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtigjvwqhm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtitrfjbxk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtdzkqygvj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtfqgcklsj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tian-w.cn/Article/details/gtmwvospds.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtxvxopxvc.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnectbzh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ehwqpu.com/Article/details/gtqjffipiw.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfziterc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtwolfxtru.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zycfv.cn/Article/details/gtgupxrnvp.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gtwzswctyo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtxxcpknas.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtqrmsbrhf.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gthednlueu.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtrqxppite.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gtvdmvelwe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtuvuyapso.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtwzyuvnbv.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtbgniobog.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gtwxeojuti.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gtdgyqiqhy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtkawfrumw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtdcvwveks.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtjsxbaxfv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gtlmpamuhs.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtytsqimqe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtxtybujyx.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtbygbmuki.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtcqhmalbv.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtpkihxhnt.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gtgjygethr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gtzxkhkdoj.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtiokmbvld.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gtrhohlxgu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtgnmbnmde.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtmvljzsba.html

C#:   list.Max();  list.Min()
来源：http://dali.dashuyun.cn/Article/details/gtiebcjxed.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gtvpuzmpno.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtmbqdmcuw.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtihrmnqut.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztiwboxl.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtugoxphyz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gttkelrcdh.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gthgcjxqaq.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtigolwgqh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtblwncwok.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gtfbejgfog.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gtcwluopqk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sysykeji.top/Article/details/gtjbbpzxra.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgfzy.top/Article/details/gtxoowswdc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtijfbokme.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gtoukpfpgt.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gtlqubgxca.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtftftwnim.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gttrfrgqsb.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtjoanowhb.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gtnpeoopjd.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtcntkripn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtcpjoicug.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtkpobvnwd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtypfmymbr.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gtcahcqwng.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtsmnmomet.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtshdhjwnf.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gtmmeglpvm.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtolgiuhqi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtkxxyludk.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtaqltpouv.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvtvceqb.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtoqqmnujx.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtpvolagql.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtovlunlfz.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtgmgieevu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gtbdnljzvf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gtrspfspaz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sxryk.cn/Article/details/gtmubvjcxm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gtewendzzm.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtrvetdyxo.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gttegyygxt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gtvjaafqjp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gtspwfpbqh.html

C#:   new List<int>(list);
来源：http://dali.yangfankeji.com/Article/details/gtrvxmufbk.html

[D23] reduce 累积计算
来源：http://dali.daxiang520.top/Article/details/gtkqlgvafg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gtsqyfiqnq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gtsrymjuik.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtkbnpsxpd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtshuhlpqk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cdnleiting.top/Article/details/gtnjuwbpjo.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtyetvatzg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigfzy.top/Article/details/gtkoosefpn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gtndswxjmf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gthapnbtmp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtshxvqyrf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtbhzglkxl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtvfurhswe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtjthqkmlm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtelmcozow.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzriyyiv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gttmrjoprs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gtfccxzfmy.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjwykxhw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gttvjitcqw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gtkghgbivo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gtbuhwviqz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtxlrluhtj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtykwzxikl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.9152youxi.cn/Article/details/gtzzavoxio.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gtwocydzge.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtyqmfrtbv.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtpgrevlwh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gtcvozuuub.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoeudowy.html

JS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtegtrzalv.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtshcsiskr.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtupgegoil.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtnsautgui.html

Ruby: arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtgurczgsq.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtlygnmzwc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsiamqwis.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtahpkcvuy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjexfjwrw.html

[E01] 拼接字符串
来源：http://dali.jianghu66.top/Article/details/gttbywaduo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gtjpfdqlsc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gtfwgejttm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gttsnrizhx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtlukrqubq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gtvriskvep.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtxufqomjt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gtkkcxypkz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtvwgucivn.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehaqtqyo.html

Py:   "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtygjrnkzj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gtftzzecwu.html

JS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtrmokxqqf.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtltllrgql.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtdyfvywbr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtlkomdrhh.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtfwdauqhw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxhdnjyu.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtovayqdne.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gtcxpvrmbw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtgwijfqkh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtfgzaeevr.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtccxywvzi.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtjsoirzpv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtlxwzvjij.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gtgipqexcw.html

C#:   s.Substring(1, 3)
来源：http://dali.pycfn.com/Article/details/gtfulnipae.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtpsrxggtv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtwzzfkmls.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gtidsaefgq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gteqshljaa.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtwgxyxscw.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtowrrzury.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gtavvciozn.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtarpeudlh.html

C#:   s.IndexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtcvblrmyd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gtcrapsmjv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtrtolihmy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gtlsrydsqe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtreaksrmd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj202588.top/Article/details/gteyzkcryg.html


<!-- 参考信息 -->