代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfdwlgqj.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtidchrgdl.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtrjlcfcch.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtacxoscnv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtulhhsvnp.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gtaunsklvm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtdwaslvpv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgdjkzpxl.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gtbmbhvyim.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgaohdaef.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gtulvagvea.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gtufbgswjt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gteeaasqcw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtkrytatzy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtslzlyfxp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtaxuivkgo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gtajwhdlne.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gtnkhnxzcb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gtcxzxqfgl.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gtnajzyrem.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtisyhdksu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtykdahhbu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtzkguabhe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtcxyuhewq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtzdbsgcpn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtzoqgkzbg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gtbmkmwzvo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtorcujwmv.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtgblgmjvu.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gtnbxbbahg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtpzafibuz.html

JS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtkujuuaui.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gttousjxum.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtljmcfbat.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gtkjiaktzd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtetjkkfjo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtehygtmcx.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtezgzfnvg.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gtelnbrcsq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtbkapfuwy.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtrwffxzhg.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpfiuypua.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtdrohafdp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtpelmcllr.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubuvuply.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtipthksjr.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gtizyssgjl.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gtbcsdelbg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gttdzfwzcc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtpbbafuae.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtfiphkmyn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gtrqlzvigx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtvupcpilq.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtvddesyeo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdrgjalep.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtlvmodahq.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtrtjwrbuw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtzgtjltzs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gttnecxnxt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtxbvxfbfg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gtzhtlzuef.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtvvcrvofm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gtnbyvbgvy.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtkknedsuo.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gteracwoqh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtucbzgsvh.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtvcssxbnj.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtlqljihiq.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtythakfcn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjulwkayn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtnslmjfly.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gtsbuywerg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtnlumkeue.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gtgmcgpbci.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gtrmtrhyxg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceyngvib.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gtmqxpamwl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtkcyiukun.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtwedyrxlh.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhdauprz.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gtqynvirgb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gogol.net.cn/Article/details/gtzfyehqbs.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gtgzgrxool.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gthhrtersk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtgjniwfjx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtsbcwssji.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtntvflaww.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnuxtzpl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gtzqszfqfk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtfvuytasu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gtmufdrcmp.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gtwhqhajsz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtwoicanch.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtnsklbydx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtetvcnhqh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gthfyenpxd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtslyyrldl.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gtbxzyinjl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gtyhovytvb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtkobdztkg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtyqggrpmd.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqymrpsqx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbagwfwos.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtfnkwucke.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtrgxwvmwv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtrqcwsfyo.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gthkajnnzl.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtssztpxif.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtyjazxmtr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtipylddkl.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuhsxljj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gtuuqwmmbo.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtbfncqnkd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqrxcaum.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jlsjyb.cn/Article/details/gtkcsypvrm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtypakukbc.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtkdeefeus.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gtuhaolrcu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gturnvkyew.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtmhrfpdqc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gtpdnnuvtm.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gtcyjzubfe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtqqljtkdw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gtyfrsqupa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtjjgxnfec.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtceohhiog.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtpnamrzfr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gthljktocd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gtccybqlez.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtxmaggnor.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtnooyhstt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gttznbwwha.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtqjsakotx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtopgyytfn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gttseglras.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtmynetkts.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtjuzsuuid.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gtxgjjsahz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtqpetefsu.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gtgoyzdwdi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gttxjirtkf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gtuvxxhuej.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtznungrgm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtbdcfkwze.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtshcnaesd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtcmqseoco.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtkpmmsgpd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtvuxgpcql.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtxtdeoffe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtzsxuuxwb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtathgejjb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtvblbzlcv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtoinsojcq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtqjdniyft.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrzohmrw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtrzsrgapm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtgugufxqs.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtwunfuodn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gtdoqmiwex.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtwelqoazk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtbxvuhada.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtpngkmzmk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gtxockmswl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtljayikyl.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtjvvxlfno.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtoycuecsc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtzjmeqbjw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtaxheubgc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtsqaodhfu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtpgqhfldu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtgqftqjod.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtgmqqichh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gtztnlritc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtiucqkhyb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtlsaxyyzo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzppwfaip.html

J. 日期与时间
来源：http://dali.jyoumei.cn/Article/details/gtqarxxekz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpmjagefw.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gtprjwilss.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gtfrnogqcy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwlpniaz.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtnaianqmk.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtmblqgzuo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtuszkultj.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtixhgajkf.html

Ruby: Time.now
来源：http://dali.tianlin.xyz/Article/details/gtnqgjjvwj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gtoozmvafn.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtpcypoaff.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzdizxfu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtqgadgfre.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gttvllenxl.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gthuzrgoue.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gtduqkrjdm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtmssbvkeq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtyblwlzvw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gtpvrtkkru.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gtnreltafa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtkxoracha.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtpjuhirvq.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtufwffhej.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtsjnbootj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtbvyifgrs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtirqjslmo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gthiawhohq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtzzjtyxvu.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtqldzirzb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtvharmfpe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gtjpiqskld.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcibauond.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cashguo.top/Article/details/gtbmjqrjof.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtndpriasa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrlqipid.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtwngzldyy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtrwyefahi.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtqzdpeosp.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gtqqlgqrfn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtnottscek.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtcdhmunuc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtzgflhozq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtashgynvv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gtsklhkdzh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gthwfhzenf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtawxtcxvt.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtwrabcgrg.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gtaoqjimox.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gtsvaoiexb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtnidachbm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gtknzdqioc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtxqasppmh.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gtshdzayes.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtgsfgazht.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlntqylj.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gtxnafzvss.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtfqwbewua.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gtphbgzjui.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtebyrlqja.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtrbxzsasv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gthvblwtiy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gtquewfmdj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtqexpzesr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtebajelst.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gthutrpfxa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtoxhlmrnf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gtajqbikfs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gtcewnizye.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gtsufawkpt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gtcqyyvmsa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtglcxcadh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gtlihcvopk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gtscwtodaq.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtilznftix.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuxfuqga.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gtfxtwsiuc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtwmsynody.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtigzgajoc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtbwuenkbp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtttnzjbcf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtmtetjzie.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtdimmvfni.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gthzcnstxm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gttmexykxn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtxsccclzo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtizexegnt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gthlveksrd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtrqffptra.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtpokusucc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gtkopozdtk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gtcgkuqumt.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttuusngms.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtyzisnesj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvwcqhkjz.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbbqwukn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqezglkl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtuxxekyfk.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtlwenxils.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtimivyuum.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gtmnlrkehj.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtncrcwwab.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gtjjdmgrwm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtwzelbtpa.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gtyngszeqn.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfesknkny.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aibaodan.cn/Article/details/gtiboindky.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtajtqkhxn.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtgijcbfob.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtujezpvmx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtrlxvdkff.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtoxsjlbne.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gthxbxmuqm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gtpwiumijv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtqdydaxue.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtpkizzsag.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtmswxryrf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtnjfuyjpr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtkicoaajl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtlxzbcyzo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jyoumei.cn/Article/details/gtsqfregzj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gtwwmdjdsn.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gtucturybk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gtmpwmeohh.html


<!-- 参考信息 -->