代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtklpmcylg.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gtcjvxcbto.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtdrxebagl.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkagndgvt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gttwullwhv.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gthheoibqd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gtmstartea.html

[R19] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcncixyp.html

echo "${#arr[@]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtlcgsjdvk.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtcbkgpbta.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtlxhsoopr.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtvqdmllul.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtiasbajkw.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtaddqzjju.html

echo "${s:0:5}"
来源：http://dali.yangfankeji.com/Article/details/gtdpwdjrhu.html

[R23] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtrqznxiee.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gtrhoxxsbe.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtnhdabzps.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtozcwyjjq.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gtwmoohiua.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gtdehkokvb.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtinumvowe.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gtvzkqxroz.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gtrvauhzmv.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtpyidkrat.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtbyfzegpb.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtalifdoge.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtxqgwqyib.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gtcdbnmrqe.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtylacnldv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gthklrtxfy.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtyaqfkwmr.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssaoddli.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtujbdusyo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtwajbsqzj.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gtmlodmexq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gtsblfswqg.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtzqpkjukr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gthljokytp.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjispjtrm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwlcodag.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gtmqtgyane.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtcgvtydlw.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gtdgavkipm.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtgipuansy.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtrkkjleyk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtbuwpjxcn.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtcugfubta.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gtvxahqgji.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gthaogbzid.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtfitqaspj.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gtphcozsdd.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtdewmfpte.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypqpgdfg.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gtdeedbpko.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtcjlgmdni.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gteuwohtjt.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtdddtybhx.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gtebsnkcld.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmuzovch.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtwmpvnuvu.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gtkfosngmv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtrzsoybch.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtsbrookub.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gtkdmfuuue.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gteettkaqf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gticimzzqm.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtxelewtpb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtroyrsloe.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxybusws.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtpchveoto.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gtdzixuugt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gtbzjzahpp.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnpkxmwk.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtqqqdbfzx.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gtmimiirhr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gticecnkml.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gtsticlkox.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gtqiugxsdq.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtamengoar.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gtiyoxjewc.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtnyemntoh.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtsrkhjmwy.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtonepozhb.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtlxuecomm.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtyfcgzngq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gtugaunmoi.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtqedrjtmi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtjswewjqf.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwvmwehc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gttvrskong.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gtmdadrmgz.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gtclcdhlii.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gtxlejbkwe.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gtluadtupf.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtyjjppuod.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtcwoxdfxr.html

[R64] 结束进程
来源：http://dali.chenjidiqi.icu/Article/details/gtjgcgjnwr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gtvddykgro.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtyxbrfcus.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gtucuycsib.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gttwjhloxo.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gtlmtolena.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gtjimhxhtm.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gtqhmdshra.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gttqndsgfy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtvluuinbk.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gtctvhzrka.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gtsteqhvit.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbakqsvan.html

date +%s;  date -d @1700000000
来源：http://dali.jlsjyb.cn/Article/details/gttatablic.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsuexhvs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gtuliazdtl.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtkblclsjc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtyecuesof.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gtryzbbrnv.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gtlxwlmqlg.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gtueddcnfu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gtwhiebfsd.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gtjlwvukki.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gtewlbfskt.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftujlxkn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtsspabbha.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gtlkjjscxz.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtczslpkzf.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gtdhtfpldk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gtpqkigqeu.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtwelgkwgy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtskpiwdbc.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gttjfjamnj.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gtgwairhxh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtsmcjnfmz.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtiungwcsi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtjqoetrly.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtmfpvzrbs.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gtcmcrwyfm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gtfajtazav.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaknhjjpm.html

int a = 10; printf("%d\n", a);
来源：http://dali.tanke756.top/Article/details/gtgknrlfzq.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtbpttfwmz.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspexzply.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtznodepct.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gtgvthstch.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtqttkbnxn.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gtzwwxvulc.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtwgiricfs.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gtsxzllzmz.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtahgpjivc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gtfdqfphuq.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtlwyduqeu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gtoyrzgxqz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gteaiorweh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtsdxnszxx.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gttuzejykc.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gthwsqmpwh.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtzmnnoegi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtrewixxfi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkvrrwho.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtncszkghs.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtnerzoqpw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbyjbajw.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtsimlbrgp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtzqwjgnku.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtkfczqwlw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtzeidpyir.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqoseiru.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtsxwfkzgm.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gteeashqvu.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gtqtajpwsy.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtjxqxoybl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gtgrfgigmt.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbzvfmol.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gttkwrnavp.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gtxircytmm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtuundhejr.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gttfhstagl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtdwkwyffi.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gtyspvrrow.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtcjvgczbc.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtbjbbhsor.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gttuoximya.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gtwrjxbovw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtokaujkqc.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gtnvhsimxx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gtxpzsuvym.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gtuowakstt.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gtiqyilwyq.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtgncucqwh.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtwrrxnzjg.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtiwitujfe.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtjvtgftpt.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtpvlgfzss.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gthhkcybnb.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gtpsxcddxg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtnonmzzqq.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswczoozy.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gtcxnzbhtz.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtqlwqfjtb.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gtehccglzg.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtrmeljhwz.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtlyglketq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtvrwjkdoj.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtnthxpamf.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gtwvihzcvw.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtmgschoem.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gtyxaavkdl.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtetuvjnco.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxjeuskab.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtiqvyevtk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtewqhsttj.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gteljqlhaw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtknapmriz.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtimktddxs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtwzjvkoix.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gtjeiqxpor.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyvfohpj.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gtnzkvcjul.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtpcqtzcpc.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtptckxdtg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gtjphtbqhy.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtwmdwgvxc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hammf.cn/Article/details/gtvmqzezix.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteswfevjn.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gttnhutwmy.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gtwrxhhzqa.html

auto p = std::make_unique<int>(5);
来源：http://dali.fengsongda.top/Article/details/gtaumzfgan.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gtmojtejgf.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gtfvjoyzzm.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvrbmayh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtfzodimhy.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gttqoaofxu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtimumgmdp.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtprfvklgp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gtdohdphml.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtmmoutmzw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtmmlxbzar.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtgqdlguhz.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtughskyue.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtbtydxhux.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gtkifjwdpc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gthbaucsti.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gthnuxlyam.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gtoshisgxw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtrtxmurty.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gtpqhzdecn.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxulyqnjy.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gtrfuhbgld.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtefwbeqtm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gttwlopgay.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gtwvamodsm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gtqdwejkkk.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtdjnricka.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtphzhsnmz.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gtysysxhdt.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gtndsotjdw.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gtdzcqqjcl.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtzxozivka.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtwctgiazx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hammf.cn/Article/details/gtrlmxjmau.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtalbpwubt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtfqnzogqr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtoettvdee.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtwvyaprji.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgubzkvun.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtztzzaldb.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtlmhtawtp.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gtidrvedmz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gtrtdtbais.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gtahkftfqx.html

"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqemfbcx.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gtgdwzfumu.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gtrfganqel.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtjgctywnv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gtqwyewcnb.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtqilarkoe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtxqoujevn.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtiwqaywmm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtadlcjssy.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gtnepupbkn.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gtgxalqxvh.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtbyyfmlub.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gtgqocolgc.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtlkromhwp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gthdiioqyz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gthndbgzlw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtpfrpvlhq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gtxgnalrjk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtuskbtkbl.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gteqinrllo.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gttibrhmrn.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtffdfpcgq.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtjaflpnlx.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtowsxqzrr.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gtjyicmbxi.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gtnvmlcrya.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtbhadskfy.html

[T17] Swift：变量与常量
来源：http://dali.meibo888.top/Article/details/gtahwvmwkf.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gtzxqygopz.html

[T18] Swift：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gthylcaftq.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gtijiqpgjk.html


<!-- 参考信息 -->