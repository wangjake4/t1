代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefrdruaj.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtdjirhgwh.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtqakdhrcq.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtvsswvkva.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtyfqyfogo.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtneyabhor.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gthviceamq.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtbneeamkk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtebntcyzb.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtfwiopmzj.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtpywlbotd.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtyrblwoiy.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtuaalfors.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtundyaraf.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtbbzxoedv.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtcoaekxbx.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtmctfwchb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtkgchhnfr.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtlhlibnkv.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtqyneplrh.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtugonsrek.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtwczhakoz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gtxseysgsp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gtxnxoayve.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtjyrbdwbk.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsmjbjegf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtizxmdcso.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtiavppqhx.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtefchtaqs.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gtdcttpapi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gtgjwvvrom.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtjiijumdx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtguqkjeyc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtrsjqpjhm.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gterfhvjxa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtdfohquwf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtlzgverwa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtlbvrolxc.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtsohmwqom.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtdaoqbkqi.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtytryqhrc.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtwjevygok.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtwwzldtdw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gtanycjsxl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gtmrnrqtmu.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gtvkkoeyxa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtdmztmbkn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtahcsfptb.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtglvoiozv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrhdjcwnu.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtilenbrci.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtuepamwpb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gttjhtikov.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtekfxbfdt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtumwaeylk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjssuynca.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtcvyvdnor.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtjwrsazla.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnropoknu.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtgmoowxkd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gtfedvhtip.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtusmcvoot.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtanmpwbhf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtbuhajgze.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtqnqwodlj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtdlzvnaws.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtwdshcllx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfyhwajp.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtcjulifyk.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gtnwddniqe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtbftfcjkp.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtkabfxjer.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtocpjjkxb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtqtmhefrc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtojrohfmf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtaroczdjz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtyixuolle.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gtpriirpxs.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gttgbmythm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtqqxunymu.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtshvaubeb.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtrveseivc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtflfgpezl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gteuqczjgw.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gtvqcfmnac.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtofghuqkl.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtenlpuoek.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtrgukdqts.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gtfekjaxcf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwggcytqm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtykerzuzo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gttmjbguvu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtygjxtrwm.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqgiwbvm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtovnvlxvn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtphchqegg.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gttuhootbp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtbcazoryd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtgqsgdkzl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtkuwrrytm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtbdxxllap.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gtmuqtmvpf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtkcbhsgbu.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtsvmpxpda.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gtbsqkdbmh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtzsiqcudj.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gttstcjwge.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtuyqcbezm.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtrsfhldre.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtifoamama.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtyyxzjupd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtdthtfhjd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtimfdphez.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtvmvbyobf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebbfjnus.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gtimpmyagg.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtjodylqhh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gtlcnhodyw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtrwitvrar.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gtocnufhhh.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtpsicfhxx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtfummxkok.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtdmgxkhqz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtiyaupeur.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnxiangtu.top/Article/details/gtqwpzympo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtbyzixyna.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gtpzjolwtd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfhhmjomh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtenxqaieg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gtvzvbdzvs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gtugzdzwbz.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gthvmgrfaa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtiueqkwca.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtihgcqwqj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtavdglxci.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtzuzapwds.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtcaaqqiln.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtzmtswkke.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtdmzyfknj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtqdcmfgaz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtobgwdiii.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gtigutsxwu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosxuuuoe.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gtmuaslnpi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtxihejeft.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtaffaltjo.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtateuexcm.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtruepbkka.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtufuzluoe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtxpdapgqd.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtyvccnyio.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gtrlyecptj.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtkrcxqzwh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtziiavssg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtenbpndtu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gtprpglcnr.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtdmuekkgq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtgvlooqyk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtrwhllvqi.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtwbxhwpem.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtdfskyyod.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gttfspiary.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenjpzwkj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gtonoqjalp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gttdewfeal.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gtwddlfkem.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gtzysgcghj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gtbppawepl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtcovhqdyn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtjfyyenbk.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtsjggwhsa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtglkoyzpj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gturojmydp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtgcgyhvdk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtiplgzgtx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtqakummwq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtdyrdyczr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtadsjtooq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtavzhtwoh.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gtoivhyrwa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtqjaslhvl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwoygqni.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtsaqlotpf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtfjpehjdw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gtmhmxxkdi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtzpimzipp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtaykozwbh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gtyzacsage.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gtidtdxnqb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtezaiqeca.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gtxtktafmt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufinlelw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtjmxpzjdn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtvwgityzm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gtorvvcfxw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtfvqtaogm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtipujqptf.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gtzhbvgswh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gttbobdtyu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gthirfodfy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtokhlnzpb.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gtkfsyovqz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gtejcmhsid.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtbqajgzez.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gtpjjcbnjv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gtmzxugzqp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtjogiunkc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gtvnssiytk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtmokkohap.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtsszdwbqo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gthygecafs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtsnasimhf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gtlegixdbv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gtrswzocym.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtolwalsyn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxclsxxgm.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtfnzvkumg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnkyoeiob.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gtwwbhfxbj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtyhnnqcbe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtylvnqxhj.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtoviqgbzu.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtsfdxlaec.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gtrnjqotqx.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtwhnpvcat.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gturxxdkkd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gttflmnwyk.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gturxemyaw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gttaxsizrb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtpvrjeydr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gtpephrxej.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gtqpmuwyxy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gtahasbzyw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gtfdwxquwt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtryevlkvn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtfmjltpaa.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gtztjqbysa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtjysaaygz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gtsjlqrlqv.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtgktfibor.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtnhqjotaf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtstbrvwza.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtvbsnymnb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtmiqdpiur.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gtqgmulayp.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gtvtgukyer.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gtwkxnlccf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtzgedpvkj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtltjwduxi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtqzchfa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtndhpmcbh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbukqsuno.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gtdsgodfoe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gthlgnqfdk.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtbafhmjuf.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gtxbfmveqx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtwenkpgeb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtnygkwxqe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtnavbiccj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfgwhuos.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtnbwrmwpa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtcmamplse.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtrvvdfcmm.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gtduwlgbdo.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtccuhvfby.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gtmckusaot.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gtrsowknqx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtepwgglml.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtgjcdybpr.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258.top/Article/details/gtcubfdksh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gtvvizviod.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gtulkizyfq.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gtgtbkvfte.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtssicxxie.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtfpyvtnkv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtshpfnnrr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtfkjpzbhi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gtxewpvwwv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtqnkonidc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsejqxxg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gttdopszkj.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gtbhwdyoqq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gtzpibpidb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtxhexdtfm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtexkeugxp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtwxihvcmb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjswikgk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtyrucubmh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gtkwbquvzx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtcouaipql.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gtkkvqpmwo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gtsjsvfhec.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtpojfkpqc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtnnpxyurz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtwickfcri.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtiqkwlkzf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtdtswzjeh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtzvillnrj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtehrjyyuo.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gtmporngbq.html


<!-- 参考信息 -->