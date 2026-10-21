代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnojydvv.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gtlkumozzo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtstlnmnge.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gtxghgbezn.html

f() { local x=1; echo "$x"; }
来源：http://dali.guowangkeji.top/Article/details/gtbztfnbnc.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyxhzgus.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtsfzygfie.html

[R33] 捕获错误并提示行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetxgguua.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdzjqpzg.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcjkymvm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtutqisdbc.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gtiyxtyvwc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtaiyrvwlb.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtzvczeylf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gtdmedfwvm.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtzpexbkwv.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtuskvyjqk.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtmmpkolnv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zycfv.cn/Article/details/gtjrhnjpln.html

[R39] 重定向标准输出与错误
来源：http://dali.cheryme.top/Article/details/gtgfgetigw.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtdumohjlp.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gtbrdxxkaz.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gtxbbuwcgq.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrljxlnbv.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gttzhhlbmn.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gtzepqnucc.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gtvqhbrjen.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gtlmrtdmpp.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gtpsvmtphg.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtcxyqkuey.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtgsetxnzk.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtubtwdhwu.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtulhuyfba.html

[R46] 递归替换文件内容
来源：http://dali.fengsongda.top/Article/details/gtwjgribah.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtdttcqoov.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gtkpprqdyr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtjpxxrysl.html

[R48] awk 取指定列
来源：http://dali.yj20258888.top/Article/details/gtoextoiph.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtvhodffdf.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtjutsvtjm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gtiwbgwvxs.html

[R50] awk 求和
来源：http://dali.kuanghao11.cn/Article/details/gtibgpnwmb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtiyjqtbrq.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtjweeltca.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gtxqvwkvfh.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtffydcxls.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gttvrgivch.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtruzlqmsf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gtwxrzgrxw.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtaenimlwh.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtxzzqhndq.html

[R55] 压缩与解压
来源：http://dali.jianghu66.top/Article/details/gtcvilmadr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gtpztmymoe.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gtrejhbfow.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtvfudqseb.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gtktuhncpu.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gtwyjwelln.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gtlrajrmzt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gtrsetmbzv.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gteggawgpn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cashguo.top/Article/details/gtdppybnzd.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtqhpykzak.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gtqkifdjdn.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gtmtxclium.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gtxxdjmxwc.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtgiaubwct.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtrdlculwc.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gtnrodkxhf.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gttynxcotw.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtfvxskznh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gttrwgdmvh.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gtjvsjtfsu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtczettjvb.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gtwwowaefv.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtfdvfrjif.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gtxamjssdp.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gtwfezgvtu.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtnrnoghin.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gthbuqmcet.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gtrpjmanxz.html

head -c 16 /dev/urandom | base64
来源：http://dali.shuidangran.top/Article/details/gtoxeyrcse.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gtukqzmqdz.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtmrkmzvgo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtbemyzyqi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtmlmizels.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtawszphbz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gthlajxmkx.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gtipuymiuh.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gthkqyfesv.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfjjhfmp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtddhfwzla.html

[R75] 导出环境变量
来源：http://dali.dianchejie.cn/Article/details/gtlngxwnci.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gtzpkbacze.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxresegi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtznblmkiv.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gtdivhlwqo.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtemeyilao.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtyauyonpn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtvklcsihw.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtpqtmkvzn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gtphpviqnp.html

[R80] 查看脚本执行耗时
来源：http://dali.316326.xyz/Article/details/gtlrrcatzn.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gtjtvkvoed.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfpbucwvl.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gtlheykgwe.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyydrrgky.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtkueyctoc.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtphgxpbeh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtjmljkufn.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gtonifbidb.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gtnntlvdog.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gtaddzgssf.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtbalfuehf.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gtxurirylw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtksqutqom.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtncddbjlb.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtsetacipr.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtgbgdkkid.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtormdojby.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gtxjsbrkwl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gtdrwebwky.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gtyesjhfdb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtrffgjtja.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gtadvkszkb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtbsvanlwg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtqepeseew.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtrjonszim.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gthuqfnqyk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtbigkquke.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gtmwypdgzd.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtxkbmjdfp.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gtarobraaw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtarskmpdr.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtrpcaebvj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtqbcwxrlu.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtdxecuhvf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtbwllzkkn.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gttsksufiz.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gtaisnyqhn.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gtnwbatesp.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtnobykbgj.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtceipvlgr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtyrhicjwh.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gtvwtxpscv.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydylpgrr.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtzbaahphl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtpxotsfky.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtdhpqxcvy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtrqxtyyhv.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gtotamiikk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjbcqosh.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtitoctwof.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtbijmalue.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gtchkzediu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gtiicggvnv.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gtqbirrjzc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gtmywckvih.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gtgngfjgqg.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gtvqnwqhvy.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtpfxlpzvb.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtzndxrqwk.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtixuwamyo.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtyqkethky.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gtyijcgjes.html

static int counter = 0;
来源：http://dali.hnqzz.top/Article/details/gtsmvmjgmb.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtbjcbxwhe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gtkuzupejq.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtcdzczknv.html

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoxkjoid.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gthjtwynmd.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gtiyecirmd.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtzqorjapl.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqchfjzi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gtcjflpmcz.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gttjqmmhpm.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gteolhzcwa.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtqvllirbm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gtvczcwmgg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtnuazuzfn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtugovfnhx.html

[S35] C++：map
来源：http://dali.yj20258888.top/Article/details/gtbcyrlceu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtwzxvmamo.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gtbgrltuof.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtiimlllao.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gtwugdfcvk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gtehhzzhkd.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gtfutuimdq.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtjjsoqxwg.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gtkpnvljpn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gttmcxqzha.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gtybajgxim.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtwrdavnem.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtvqdqauyr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gthasnmukv.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtzcjxpqyo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gteepzopko.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gtelchqjlh.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gtdumakjmk.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtfpwyxspi.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtbgwxweia.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtvrgvdcxp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gtuusdddbi.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gtvbrnszvd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gtnwlgmpch.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gteytwncjr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtuvnpaasd.html

[S48] C++：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtluajtblf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtwrcxngoi.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtmgavyizd.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gthlzabvza.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gtbiyoqsrz.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtwubbphns.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gtlpspfbkh.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gtvclngrum.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gtmldznhwg.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gtkhbvjipe.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtphbzfozp.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gtpkazzyfb.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtxwqymvkl.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjtdpobc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gtzsnzyrvw.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtvuqwlwnl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gtutvuwpaa.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtcrmdhlrh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gtubsloykj.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gtgaasstlg.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtgdnkheuu.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gtlcysmjjp.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gtwpzmxsez.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaouqakw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtifmfwrhb.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtmxctjhii.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtiuurhhrl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpmpgekin.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtuuxxdigu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gteobagiiv.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gtvmsxxwem.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxuyrxwk.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtxvpuxqrl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtshryttaw.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gtlldjlojo.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtyinqkuuj.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gtakyvvrqm.html

val n: String? = null;  n?.length
来源：http://dali.cashguo.top/Article/details/gtdozptaqs.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtrcrpbyju.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gtfsemttmt.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtcazcdcse.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtuuvgwbff.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtihpfydzw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gtpghjnlpz.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gtnyxamqmy.html

data class User(val name: String, val age: Int)
来源：http://dali.hammf.cn/Article/details/gtkiwlphym.html

[T09] Kotlin：扩展函数
来源：http://dali.ivvv.top/Article/details/gthxleijid.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtudobyuaf.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtcxmqiiqo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenzaomai.com/Article/details/gtnnrbgzlv.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gtdorzsobw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gtlnqwwkoi.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtasyfobbp.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtcpxubpme.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gtfzqsllyv.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtfsbnfcws.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gtwcexpkin.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtjhhpfugu.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtajxhrneu.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gtjvezmsrw.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gtazqjkqji.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtomqlptsg.html

[T17] Swift：变量与常量
来源：http://dali.9152youxi.cn/Article/details/gtvteqgvrd.html

var a = 1;  let b = 2
来源：http://dali.hnqzz.top/Article/details/gtibdbewyq.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtrkmabrdm.html

"值: \(b)"
来源：http://dali.shuidangran.top/Article/details/gtyjpotrkx.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gtpkopbwmr.html

if let n = opt { print(n) }
来源：http://dali.xuetiantiany.cn/Article/details/gtexwaygop.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gtfmprsxnz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtfsrqhnos.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gtwpepljvk.html

for x in a { print(x) }
来源：http://dali.sxryk.cn/Article/details/gtqmplehjw.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gtvrpziumv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gtrrlnyvym.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmdddrba.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtzinpvdot.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gtmeivqqfs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtemjyaijh.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikrialbu.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gtpyueauop.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacnexjkc.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtermhykox.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtgwgmyccw.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gtgdqolspt.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gtjxmjogni.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gtzeoweadw.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgcquqdk.html

guard let x = opt else { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gtekepbbyc.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gtuyfybvqc.html

protocol Shape { func area() -> Double }
来源：http://dali.cucudq.cn/Article/details/gttjbdxwej.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtthoyhcni.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtgxmziagy.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtgfjkyjmk.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gtvbgxdmab.html


<!-- 参考信息 -->