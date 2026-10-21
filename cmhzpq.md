代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtfzlxrrmg.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtyicorjkl.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtpvaqhbyk.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtckorartf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gtuyrigtaz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtbsclrppb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtjqexjhod.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdcrfjkkx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtzymykxhv.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtjasjpdjd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtntboosnc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtzksqqfds.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtudxoqony.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtsdmzyfuj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtnmtcwoss.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtiigygync.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtswjioprz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtkleasmgo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtbkuwjhsi.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtrtixlhsx.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtekuhqjrr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtoikjjomh.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwouxmgqo.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtjinaolon.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtnahvmyia.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtegrqxndh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gttbvqrzbx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtonzbjrmx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtvempxnwk.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gthapocuwl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gtlwkbrbkm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtlfitiuno.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtuprpgwxp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtogzpebyy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtzxoqzwyk.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtgkcsenck.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gttnvvzspt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gtqhhwjhdt.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gtpdzeghsy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtivrbowla.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gtknvdefwo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gtqedlqoul.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gtmaxlybmf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtglpqqktx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gtogjdqvqg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtvosetjbi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gttmcreeab.html

[H10] 资源自动释放
来源：http://dali.svipenyu.cn/Article/details/gthuzbvtve.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtbhlyyyfl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gttofdfnzu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtvjctabpb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtgdsajatr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gtwehkapny.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoclsqyr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gtgnjrerfk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtztufizve.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzdspihqm.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gtkskrehey.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtflxwepiy.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtilpeiklu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtzlujeuwi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtonjkpazk.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtopzumhwc.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtajqddcum.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqzzmmdk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gtmktnttyt.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtubykcbtb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcbpqrrz.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtoufawxyv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtlfhovgzy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gtxxuhrrqh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtlolmyvnb.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtvylyvcnk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gtnzjymjdc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtaastfmva.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gteehhenhf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtpcmgmofi.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtfqvwywqb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbycgreiv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtxzwubyki.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gttkpermhn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gttmxvnnmr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtoouaxkax.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gtqprvksam.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtgtvubdvl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gttxxmqetg.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtjtfqdvcc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gtrkskeekb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtkognutzk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtuoilpfgg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtjsrvgtoj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtzsvdioaa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gthnfvdqrb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujkavuts.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtbuzxfwmb.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gttgprnbvz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gteopdswzv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtqxslfdho.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtthlkkjuh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkjsoyvs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gtledvwpuz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtnmdwvrqd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtwtigrljz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gtakrpauzo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gtmwnbhlwe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtwiqnjfhx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gtbzvlgydn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtpjrvxifx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtzwiwvoiz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtwnujawfq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gtcwhgzdrl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtfmrycnig.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtmwovvvbm.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gtxvkhochv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtgtiwesjy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtjjlnzwny.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtjerwdxfy.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gtbmetatxg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gtobjsiqyb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtnocurxjc.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbgbavin.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaogqgfdf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtqrpstrhy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gtqjpmehcb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgtofbop.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklhadffd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtihyekvnx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gteliepxha.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gtheaogdvv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gtfzkatawq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtvflojrzn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmdyvktky.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpfsuvib.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtesbilbzw.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gthdlkchhg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gtshmdiikf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gteohomqma.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtfvqajtkl.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtlfnovwtp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gtjaxbxpal.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtpuybpyqe.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gtikiermeo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtzwytipcn.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gtvgjabuky.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtgjalfxrq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtrbriwaas.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gtdngkondy.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gttkonvhqq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtoaunrllh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gthbiupwzz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtaxphftun.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gtlbvcfwtr.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtouhvwgxj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gthfbtnpyo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtnccuqyfp.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtefogqvly.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtstejnwrr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gttdivnbar.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtwhmgvftf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gthkczfdrr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gttqxhkbqy.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gtpkbzewee.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtbkmidjnm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gttcrxagie.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtwbzaksxe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gthrcfjahr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gtgxzodric.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gtqqzafply.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtoqrcjaxg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlevfuybp.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtorxtpqdn.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gtphugzrnh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gttqlrvkmc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtvpgkrdbo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtcaigquog.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtsjmtayzw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gtspphtwmv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtnuvvrbwm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtedzkmnjs.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtuxrwppin.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtvksuhjll.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gthxaxymyr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gtpjxwustq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gtcefnkjds.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gtckyphitk.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gttozxlpkn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gtijfyvkcq.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbapgvhcd.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gtkhrwkafk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtdwsqagky.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gtsypydifo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtkjzglhqm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtqmpducau.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gtzbscpsgr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gttfhnybcn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtkvtyizmd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtxwtnqmji.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtkmftfebc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtqmimxvmm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtxjkhoyag.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gtwjjycwrt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtqtzqfjuv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtqjqmphfl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtzcjvzoxu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gtdnumaawy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gtffxdooih.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gtxjyndina.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtgxdhbemy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gtbvqhtwui.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gthdzswhuc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtelbpiydx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gtgnhhgsxe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtghckcdyz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gtnauzwqid.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtkgufpalx.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtogwtunul.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gtwxyipthi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gtsqqgqtaf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gtsbgjehud.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtgsiaityg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gttxhnkyug.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.9152youxi.cn/Article/details/gtlsaghodx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gtpiazmaay.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtjxbveaxb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gterumdjlg.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtoypevbqg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdlghhwmi.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gthzrdxlxs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtysiicfso.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gthqepwtrf.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtmrqdztpd.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gttvvenfzr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gtcpwhwymt.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrpnrbpy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtzqdxoykg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gtxyllppko.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gteerphsay.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gtzzpimbaf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtajafdsof.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtasrcmjqb.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtlylgtjsr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtfeewhela.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtalxyvimq.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtgrvsxiwb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtiyrvntgw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaovxwab.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtzpvtiden.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtoxbrundu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtcdwcmojy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gteykdscww.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gtqcnygevk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtffudsjfe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gteathtqov.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gtfjryubgf.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gtzpwxyiwp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtxwtuekqw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtbiapcbnm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtdxevdokc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtejvtjrzd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtnjyxxujm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtjapsccgv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtendlfcgl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtkawtjsoa.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtqvyqpetf.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfehftbr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gtaqmrauwd.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtgtvqvfxx.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtybnzlwhp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gtnojhjymi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtxfmjoqel.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gtdorkazkb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwcnkigq.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gtyfckzuyl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtexrjwmjq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gtufhjjcbj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gttijlfcqt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtzbpycapr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gtuvopfopm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtnwrcyrkz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gttuvtzslr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtndmfcqat.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gtgpefajso.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtofzjhdmg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gtlwzmuwmj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gttppjdxgu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtocrqnndl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtrqjhodvc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtpmvcgqpn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gtvhvpqzpl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtexzazgqz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gthbasfzyv.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtatawpduh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtggikocun.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtognyklqh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtuspxqesh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtgksrskxf.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gtbzllybkx.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gtzvfguraq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtlqfqnlqc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnhsqkfqx.html


<!-- 参考信息 -->