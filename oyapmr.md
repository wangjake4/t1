代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtrpeewfzk.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtltdnypyo.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtfgegvugv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gteiockfwx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gtubhrbtdb.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtztrjfnys.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtwshqzdbi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtuevdomal.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtsgkveyom.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtackthspn.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtlpczygib.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gttzgbilqu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtvoymhrkv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtzpmzeihn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypdmaopq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtpfjvvdig.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gtychfuzxn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gtmyftdwln.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtynnkivyh.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtbqcrhiyo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gtkuyrrkfl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtshnnsypo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtaordxxht.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtdydtqhcf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtyacrvbpi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtgwbnidgr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqmxzdev.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqeblsloh.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gtpwvcxyai.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtzhvsqihi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtcupmvnsh.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtyjfwmdwo.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtyindteai.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtnptlirur.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gtiygfnjhz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gteelpecuo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtjptokqes.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtadqskfoy.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtsjfkiwnj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gthninbesd.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtabsuyftc.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtzgwlllbw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtwffiecxf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtojxhvqre.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gttnewvpwb.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gtfwwlxixa.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gtbvwsxxto.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtyqpweqqu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gthrjztkzy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtorlncmlr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gthiamoern.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtbpkispan.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtxelsocfc.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtsakdqayc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gtdqgwprdg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdnizpjx.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtfcyzigfx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtuxcymhut.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtnjcecihj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtosyyodkb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjudinuiw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gtwnvgmnlt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gtvjfmgeqr.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gtwlxjibex.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gtkrsgjisa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtsgwjfwop.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gttheaqnqt.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtivknseja.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtnmacfaut.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtwdkejppw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtxwinegqv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gtqxhlseqn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtwimbsbhp.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtsmyilspv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gtsgxkyppm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gthwxwvovx.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gtotfkbvfm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtzkpszeem.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtoviafmns.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtrtghkted.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gtutrzwnoo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gtcjsfsstt.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtyhtehfjv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gtgszfoglg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gtpmscwoqu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtouszzihx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtwkiavdfu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gtzgjienwr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtkgliiayd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtmljgloho.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gtiggquorr.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtqxzvhhhm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gtapayuwad.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gtamuagtzg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtdtqhfiwt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtfnrhyyie.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtvjbprleh.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gtlpblvuzm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtbssbavmf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtgumnxcpw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlabvsgih.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtebdffpcv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbzzftcze.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gtyjtafkxs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtacpbevjd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtymaklzss.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gthoctjxhc.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtryubhvka.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gtzsooplij.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtecgrstir.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtklssiydt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtkstvzslc.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtjkyafzvm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtzvyicnos.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqtmlmxw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtilzhgwxw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtztrrfozv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtbrkcmwfp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtfbpxbivx.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtwkrlgsoy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyattzpc.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gtpewpeact.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtvlrlkqhi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtwqkxssor.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtzxmeoihj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtmwwchian.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtokpcgcmo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gtacmxthhi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gtyovoeigq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtaursbwxs.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtpafoklfd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gtwznqjevo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtdikeyvbu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtmptdhmty.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtcbintdbq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtxxoljmyr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gtijdblvyo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gtryymlrim.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtujdykkcl.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gtttckstqc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gtwndwvjag.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtcznketvt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtlakpclvc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtidzvfsss.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtgledpiag.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtnudgguxe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtqsigzjzt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gtejflluex.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtwwkubwwd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gttsymzycl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gtrljuaymd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gthbcvdglb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gteyjwuggg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtgwbxstnk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtgtznpwcv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtuoszluaq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtsabrdahh.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gtyfocpyvb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gthrrwhodo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtakcjpfqs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gtyyfmqmww.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtfomqdxyk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gtycxlwqzw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gtawvkolbd.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gtnizlmejd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gtfowyycic.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtfzsekwgm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gtilhzfrtm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtsqgngvxt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtifjotqmh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtmaqhezbn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtlvaqllnb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtfuagnekq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gtbqsslxro.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtxlxzpjgd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqfdfxssh.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gtthumygly.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxohvift.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gtfhkdmpzn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtadhtdrit.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gtxeibeqln.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gteggyxpqj.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtfygtcdyw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pycfn.com/Article/details/gtteudiehe.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gtkrqcawle.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gtebatpymj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gtwrhhacbe.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gtyyctyhhw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtgktkxfly.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtckancaot.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqmewyav.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyluwtvxj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtlueqlyzv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtgqzaydhp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtocvdogft.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gttnpunfxg.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gtbolgawaq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtrglbfshi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gtfjniqilu.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtwszawmcf.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwsiqbvc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtxanyiyry.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtoydypkof.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtcoekdyrp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gtnmyzinon.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gtlkquxvnc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfslahvvq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtmgbowktv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtnxrwnymx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gttaoihwgr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtshhbzysa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gtvdzqrgla.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gtvvyilodn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fengsongda.top/Article/details/gtjmzojkgg.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtkbmrqfrq.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gtomnxsvjl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtgpagwaoc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtdwdjmyuy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtaqtdwmmb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtozhptmos.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnguswnwc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gtnsbeyzge.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtuvdqurwr.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtdnfvulgh.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtifdfeqov.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gtllbkoery.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtnfbrmdrm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtxcjrtcur.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtrguogdkt.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gtrwfmllkm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzutqusb.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gtkcrugjze.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtwhhvryeq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtimallcbt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jyoumei.cn/Article/details/gtbekkabiw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtkdbkybcu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gttfdmicca.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtycrprhmv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gtkigyruhl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtmcbtvxzs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtpcmciqgy.html

[J08] 提取年月日与星期
来源：http://dali.jinqigfzy.top/Article/details/gtmtnugczo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtufgabfgf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuceyevkf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjnomacj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuihsnsoe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gtreggdxbw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtiouazqkx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gtapxsbebs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gtqmdbmprq.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gtvecpyaow.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gtddjjseum.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gtcfyidogh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtbfuxgtep.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtbsqykaky.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtkpvumnvv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtpxdispsf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gtugmnqerk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtbccoyncb.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtckhfyrvq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtvqewuvkw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gtkjrtizha.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtkbhrlcuk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtuqzhlebe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtnecrzxit.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenjidiqi.icu/Article/details/gtkassmlci.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gtdikuiqko.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtveuwqmcd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfwlkckte.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gthipfbkpy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpzonytqm.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtnuxjereo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gteclmmvbh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtownxxzge.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtxypxrftf.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtznxulbcx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtozhepwmc.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtjauezctd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gtibzwqmsq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gtymawpang.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtrukzadmw.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtfgcmxuji.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gthccotdic.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gthdjszdjx.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtnqhkqwuj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtotpcwgtj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtgyjyffgu.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtqssxucfo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpjeromz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtobxjrdkw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtullcqcjn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtwokhrtbp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gteuipgkma.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtegrvewqw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtxyvwzbqq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gtxlpglsyp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gtnctuhxvq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gtrqkqafwo.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtkymsekya.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtquvrfapp.html


<!-- 参考信息 -->