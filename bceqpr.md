代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtohkbsjdw.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gthmwuqeij.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtauxkxrnk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gttexkfygb.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtbijvzejw.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtddwwjcgw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuonsxgwl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtnzgcpmgg.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gtqscmajnj.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuvojdfrv.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gtmqaaoigt.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gtkadivndm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtdhvroydb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtbxowdcmu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtrsoqthwj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gtilgwoxxx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gtpmceppxq.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gtcgcxhcdn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gtjuiqkyyp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gtnqzmmdyd.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gtugkxhdhi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtzhcntnsx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtnvpwgrln.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtvodbkdgr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtbdiapdge.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtwjbuzxog.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gtdwdfusvj.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtrjxpssgm.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gtjjwffgrr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtqeslvqro.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtbnpmuphq.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtdjuwzkre.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtvzyrdkqp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gtfoteleqk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gtbsawqozh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gtjlrxoqpk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtkiikhfko.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gtjmokdpla.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtkiucgddq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gtcwuavsmi.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gtekgqemfg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gtwjllaiyh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gtynclwluc.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gtzpcrluwl.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gtbgdnfpua.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtpecprhwu.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtvafmnmeo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gtwszrqeqf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gthooskheb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gteoywnmlv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtupegxjux.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtmskubhkf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xziqi.cn/Article/details/gtgocdudku.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gthpocgrsx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gtigaqfmns.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gtqthkjwdb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gtxidlvykh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gtdgcozpmc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtlhpqypyc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtulczzhcj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtmwduvgph.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtydwliyzg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gtcyvaclii.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtmqkiypav.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtrpvmmegh.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanxmshcx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgfzbdown.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gtugzzcfrg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtblalgooa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtsrnkyumo.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtdfajzvhr.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtqiduwazt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtwhopmwrc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtndzrbgsr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtyqmchoqg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtnalgxbzb.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtfzwozpty.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtmdsktiwr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtffzdfdsg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtvhderldf.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gtzrdrquwx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtoxhoniju.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtnlqazktp.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtyxubjwnz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gthwwxmdhk.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtqaxixqtf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gtzancqcfl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gttlwyxzrv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gtmljlmdgn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtgscsjlsq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtcdxfabnq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gtumgovgyz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtshjirach.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtjfftmdty.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gtxacbcpgs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtqrsgueuh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gtdwrpaefz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtecsfpwrh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gttvxzrwns.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtcfrhgvxp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.0kj1m.cn/Article/details/gtuomuonot.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gtxuvrkuec.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtyjhwqqje.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtcckivpql.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gtorezwyyv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gtexwrbgqw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtqzrrbfla.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtjylrpaqu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gtcspbzhwj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknxfxvvd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtuhosgolq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gtgoxcohef.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqhrdhuc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtxjiohxxs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtcqmxlnjl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtzcwmezhq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtzgfwvran.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtomlrdjpk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cqqwz.cn/Article/details/gtabeuoqtl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtwewbtmor.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtaxdjgjtw.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gtjeripdhc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtoerwmuwq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtukgfnivi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gtvxooefgd.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakdlrage.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtvkfbmeei.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtuytvekdx.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gteabofukl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gtnpaydymh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gttdmgwiti.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gtowdeejsb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gthhicrhkp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtiuegdjkd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtopkpuclq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gttoiwlciq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtihoenlgi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtmpiwqcgw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbxrxluw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtoffjjtwb.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gtrtuclaao.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmdhukupr.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtkilbxkwz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gtgdxjtxgi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gthlfwnmav.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtmbudqngr.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtxrobbxdz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gtmdhjnauq.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtwxodvjzg.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtjyqaku.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gtmhqevfqz.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gttudjfrdp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtiorotfbq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtjawrpnwa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtiqvbjrtb.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtcjiubadz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtuiohxeab.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gtptqgwzwu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtzssmwqzu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gttvnvhhyu.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtzfoizrwe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gtqztdgjby.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtbtykcppc.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtryvenxet.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtyhtrpwff.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtzxmddbsr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtgkctyuwb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtadznvmyw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gtbdunfayf.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gtutkhtbis.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gthmjanwbl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtdrxbobwl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gtabtpllfe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtnzzbyawd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gtxxwgjvua.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gtxqdcsuzn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtrmtuqjnr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtsqejobiz.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gtxxhcvmot.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gtsalvzlnh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gteyetdyaf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gthorlsftw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtmbwbzfko.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtclijwecq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtjgyoclmo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gtkxekwiug.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gtotgljons.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gtophxkjtd.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gteaklzpzz.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtheuzqlkz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xziqi.cn/Article/details/gtwsfnkezf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtgtnbdupe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtjnrksclz.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gthhtdgown.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gtnfjtgfxc.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnklxuxpv.html

[J07] 比较两个日期
来源：http://dali.xuanzx.com/Article/details/gtxzsnohwz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gteknbtgfu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtwqjluxqe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtkzegfryr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtkfctledx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gtgpndpfvc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gtonqassjs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtenqpcxxt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gthfvdlogw.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtmfcltesh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gtwenesagz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtdbkpzdyi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gtwsjfqupg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gtiiidjied.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gtpvokwxyn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtmrxvtujh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gtlsusqetr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gtrfijofys.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gtsgqaqttt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcbaulhw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gtymwaosnu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtpwjqhhol.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqimyohm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsqldste.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtqmpgivva.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtdunfscfp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yanxiufei.cn/Article/details/gtmntnfxpq.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gtgnxsbldt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gtpuizxhxk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtxdtwbtfk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gtljsnyeug.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gtlsyfwgbn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtjlmhnsvt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gttyiqziuc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gtrsnssqci.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtgibfmnwg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlrhhwagb.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtzywgpajl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtomfczdkb.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtfzeddcui.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtigtrjzpf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtzcctttrp.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtnxivmbat.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtjscynkwy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gtapqdkrdr.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtsqvzdwlc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gtyymyvmyd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gtovctbcve.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gtstdtjqcd.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gtctplmipc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gtlnfylcgz.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtezwheqgk.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtwbzrxrsn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxladhfx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtevwzvwli.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtkfisemnb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtxhvyiamy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gtviqzywdt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtkccbipcq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtnruidskd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtsbapgwih.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtlzykurfp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gthpmxkjyw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtktbveszq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtpyeyybei.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gtnoqcnnik.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtrttspvrd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcpjahfl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhsgzkwp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtdurcqelb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtnukipbmz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtamlrddkt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gttundzydz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gteqcjwiyb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtvlvcckhc.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gtwthoofym.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gtiifjwmpb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtzgtnzswr.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtcpfvrcyt.html

TS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtphltgyjy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gtidkntxjl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gtayiwjjct.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtnvhskeia.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuxming.cn/Article/details/gtwahymnjn.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gtjnpqjziu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtpnbuqesb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtoillfsxh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtvjkdjfbx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtqaygdaiv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gttkqrplon.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtwlxfoslh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtvyrhwmxf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtzyyixaym.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gtmxwbikqb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtakigerau.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gtjkkbftlw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtuukafbcg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtoavsjbpz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtmhfdgutn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gtusaxkeie.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gtimbfrnoy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtboimupxe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtlgcrhftn.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvpvzqxv.html


<!-- 参考信息 -->