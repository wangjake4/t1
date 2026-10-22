代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtixypbubo.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtviwowzyg.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtuorlphxw.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtjlxjsere.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gttfyoqyvz.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtbsbovwcb.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpgbrobi.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtlxmplnxm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtmxhcobtg.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtueomqoir.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtvmpnhuwz.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtwekdngyt.html

Py:   isinstance(u, User)
来源：http://dali.xuanzx.com/Article/details/gtqkqadxia.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gteyaznlbq.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtkpkytzyd.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtmsegjzbl.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtudvbeast.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gtpvvkxose.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtaueodwnn.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gtjktrjuxw.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtmxmutyzt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtthznqdla.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtzctxhgis.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtklbfauyr.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtmiwwmrjn.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gtgikeccdq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gtdrfdqbjj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtzzhrergj.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gtfrcjdynx.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gtscflvxsq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gtluxntaom.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtfmbaflsm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gtfvsqzvhy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtcgdsub.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtftqiuimf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gtyjucvomm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtpujkclzg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtelvrilet.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtdmrkmxbr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtpdliymxe.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gttvcfjjlo.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtlgaepmih.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtwaxgcavm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gtfynuhwxz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtowchvphw.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gtwrmhwdeo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtrzzoemjk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsslvkxuv.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtarunshgo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtikavrztk.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtrwbqzwgn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gtnbkacdqz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtzalvmbrd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtlklusyex.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtangkanol.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtsmcjugye.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpunxzkkj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtusxqyhfr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gtpbpwxdhc.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtmfzuytkv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtujtspjzy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtbcxkekax.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtwaezjvvb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaosrpaf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtfqppnmni.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabsslgdf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtqgjhccbl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtfmrjitwp.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gtaxjnohlv.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtxenyahav.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtqprvtism.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtzypcflhg.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gttznzzmxg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtloywcvqt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gttkwbknvk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gtbqgydcvk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtistkrivl.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gtbpfogynq.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtqogoaqtq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtpgwpzjzb.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtumqknhft.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtzbtlawmh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtxlzhsxcg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gtnqfauipw.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gtzjgjvtxa.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtggnbmbad.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtcnweapvt.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtgtewqiji.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtspmpooti.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtymbpfxjs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtshfwdhpm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtkvypfqhc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlemdipph.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtnwobibmi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtoldnpcsi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtcxqbfgha.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gtbechvywg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtipcyfryo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtvhfyxzht.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtavmyfvrm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtwsdgrhqm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtirvzokeg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtvvgmpcdw.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gtsuvpkiyv.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gtujpowprp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gtewugfmmw.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gtiozflykr.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtqtpfhrnd.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtfzjjmykk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gthwffdnfr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtfykzecbb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtnqfhfwso.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpeiauty.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gtmfkglryc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtizgyrxbu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtqaexioiw.html

JS:   e.message;  e.stack
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwvcschr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gtmcjttlie.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gtapvxwscn.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gtbbjxopde.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrgrstpp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gtzcsuhsdh.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtpbryoghu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtuiwcehen.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtyhhhnvdx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gtbmidcqwj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtsevihriw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrcdznsyi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtyishqhgf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gtzqpbbvrx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgufenzy.top/Article/details/gtfjcsazyp.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtagurnull.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gtartxgowj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gtqxsggdip.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtebdgzrhm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtzjvjriei.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gtmombxetx.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtrnydnmwv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtpctleynx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtqasgruno.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtomoeqwqe.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtelyljeof.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjulzlvae.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gtkcrmrxaf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtzqyjcbft.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtvytrhxed.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtcqjwivhr.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtehpzuehz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtvpuetgeu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbqzihtem.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gttgkcurjh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtdjdzbdze.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gtiuizqtpl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtnyiakwrb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtthnzjoga.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmvhvkmi.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gtvbnijdhy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gtjwugpwxc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtrjhwzful.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtppdhftce.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtfaanmyfo.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gtatplpeyg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtdbjlogqk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtyztgzrdl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gtogzmdiwv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtuqvmcjfv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gttewzusgb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtnfoudalb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gtmnzonhii.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gtgdlqyduk.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gtdtmdjqbb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gtkeeigbfe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtkcrfhxmt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtcefmihpr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtcxvoawrf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtkjciszbt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gtjiqtxnfv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gtsdvrtfaw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtmkmymtjn.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtaxkpdffp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gtqjpieyzh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthundocnl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtkmpdbnvx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtsomgjfnn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gtfnykymtv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtlvqnmunj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtwocjjtob.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gttrdukftz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtmgcxdplg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtelksvvbg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gtaagfqjfa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtkafbjkof.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtbystmjbh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtdktpyowy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gtkaueigvi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gtgfusrmpt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtluznfvqi.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtefbzlmjl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gtorfqbjjc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtnirwkpsf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gtxikvdplj.html

TS:   /error/gim
来源：http://dali.andypj.xyz/Article/details/gtnuxgamnb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxodxekek.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtwvsbqgpq.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtltigwjim.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtviumgnjp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gtbeqvmufe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gtewtagtfg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtwmpevnho.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtsrvebdou.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsktgdff.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtqdvmaqai.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gtjzszdmim.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtzkutdjen.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtthbgbxmh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtupwxwzey.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtdqkdfqly.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttbiinub.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtspdinhrj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gtahwqrulu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtqudmnwag.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtqqihytyc.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtboxbceax.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gttafpnopv.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gthtezycog.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtalvirggz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gtekimhsmf.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gttikkiauf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtavjtokca.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtmsvvfyae.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtgnfrhcrh.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gtgnjvugwc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gttofsxxct.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gtuntuxsdy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtgmatpeim.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gtluajtnia.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gttvbycjlb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtvnyxjwuu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gtffjhrnza.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnppcxfq.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtugzjhfcy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtifxbjikl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtezowzniz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtztxbmwtc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gtxbfoqkhy.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtoaoehqyb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gtovzwypxo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gteediupzb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtzjhnlqbs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtsfyahduz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gtwoxjzpho.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtjdyusobk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtnxvichre.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtujjdzspu.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbibxnfes.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtafigkevj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwnkkeac.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtzjqlnfxi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtokntlyin.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtqnsmoqgw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gtcfkxmnsb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gtvfgqkaqa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gteermaieu.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtbocqvrpa.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtjoevmzht.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtuhhkskeu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gtfcduibtk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtgxymvxtz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtuhfclfnz.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gtiwokajet.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhongyouzk.top/Article/details/gtrpcoatpd.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gtfpmosmch.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gtrexcuuvb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtrkangoag.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtinfshynk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtblqrklzd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtdzfaetrz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmvijhww.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtapjugxhl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtnbbzeimd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdnjpowz.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gtdgylgjoc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkofshklf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gtyhyfxyoq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gtpwhxmwme.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gtoowazsph.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hammf.cn/Article/details/gtenadmdap.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gtfskvpjof.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gteolvlfhj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtshzzuhqb.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtwoangoxe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gtnohgfpff.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtixgtygoe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtefejwaiz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtjxsbwilq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtfywokyfg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlbswohj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gtvxbpypgp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxmmisej.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gtuzxhuuze.html


<!-- 参考信息 -->