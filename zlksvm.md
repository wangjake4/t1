代发 wailian999

esac
来源：http://dali.tanke756.top/Article/details/gtnjtsuvjb.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtifyviuxf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gtzirvjggi.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gtinajfrmm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtjnadppek.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gtffiemivi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtpkumgnsg.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gtiobctxmr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtxordtpch.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtqjxgwids.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtjvyuuruq.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtqzrjqiah.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtxdsqspsj.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtgfumtvwg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtaahkqcvv.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtzjgivcpx.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtghnsqvrs.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gtpztpdgja.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gtmznapxnz.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtprtpxvej.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gtccpaocyt.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtzyrwnjnv.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtprzpbwhw.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtpnkiecfw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gtwscszrxz.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtcvyzxipm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gtbnyulvmo.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gtiizyrfms.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenjidiqi.icu/Article/details/gtotymtblk.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtoogygjbl.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtfbvpqklt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gtkoqtdpcg.html

echo $((1 + 2 * 3))
来源：http://dali.jqgfzy.top/Article/details/gtruhdobwo.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gtzasreuue.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtsdfrmmtx.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gthxmtfnrx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gtepknzfcf.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtruqtgori.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtkrrfyrvh.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gtkfyfdvzy.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gtrezyqwcp.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gtigufvwbg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtqncenlin.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gtlyyckmft.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gtnesvmexh.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gtezqzqort.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtapvlkpsz.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtxbcmlbyq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtmlrwstjw.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmidlqgfr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gtlrlblaiq.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtievgfwbu.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gtbbhhbyay.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gtcfjtbrem.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gtmytwvjkh.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gtrwdiahet.html

cmd > out.log 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtyxkauhlq.html

[R40] 追加写日志
来源：http://dali.hywenlv.cn/Article/details/gtpskkpyff.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyikdizgb.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtmubowvdo.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtuzmtibtu.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtgvydoprp.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtqytezeug.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtfrkofqlp.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtyplziaor.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtltgbpytg.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gtomvbwwyc.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gtastuhqtp.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gtkglwzwnx.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gtnuuwxzcq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gtensnnaww.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtkfoozrlj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtitcdrjfz.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gtpbiapjoc.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gttxmkncll.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gtlhisxybo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtcblcpjid.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfujvdzck.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gttgxfjaak.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtrrvmnjmu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gttzznparq.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gthvfktwhc.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcndllrc.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrtjkfnx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtnaxcroye.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtjwvuvpog.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtnxdaqznk.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtuvrckfxg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtinhkkvey.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtjfkbdddb.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gtajsyqqfs.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gtzqbjzapj.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtolukfjcu.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gtuxmmntpb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gtdoceumee.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtfwcmscrf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtrbrrguqv.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtbppeogjq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtlcicpwjc.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtazghiyuh.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtsfocwfak.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtjxjxmlmu.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtuqshcrwz.html

[R63] 内存与进程
来源：http://dali.yueranfly.top/Article/details/gtxshsxxrv.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gtifehyhxv.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtobwqdjnr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gteatuhmlf.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gtxdcbqjdt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtbnhmrjxm.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gthityzmhe.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gtygknpypi.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gthlwavkat.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gtoajotmyh.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtgnkgpvwx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdaghozn.html

[R69] 生成随机密码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkrrvyae.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtvaqiylva.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gtiydzpkvg.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gtxpidzipp.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtyjswnepc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtzuohuznn.html

[R72] 等待端口就绪
来源：http://dali.aizwys.cn/Article/details/gtjcxxrzki.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtkunxtfwi.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gtqsqsqlkt.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gtrlfopsct.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtgculnbqh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtbfsnrwqj.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gtpyovlalj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tian-w.cn/Article/details/gtbyuydsyb.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtlnjkccoc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtsjmgrwca.html

[R77] 读取用户输入
来源：http://dali.yj202588.top/Article/details/gtqvozkape.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtkzzfhzmb.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtjkkqmzhp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtlmcxkpej.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gttcffppqg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbhvyswb.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gtbotilhbh.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtcttesqfd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfheyuomy.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtqqfpkssc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtykoirdlv.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtowvyxurz.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gticvfwgay.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtinzlmonh.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gtbnjcigse.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gtzrhjmwiq.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtqznnqadf.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbrnqjrv.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujtqccsi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtxygytjik.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtkptqissv.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtpeiaypuz.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtmlrmecjw.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gtgzwfipjy.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gtqecaozhr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtnycxzrzr.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gtpxctbmnr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtuunhvhoi.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gtvejenzoy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtrsoxccnb.html

[S10] C：指针与解引用
来源：http://dali.hnqzz.top/Article/details/gtshkiiusc.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtisqnhlwt.html

[S11] C：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtdspemdgw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ivvv.top/Article/details/gtemadnpkt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtfrqopkvr.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtpvgyttfb.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtipwbveqt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtixfjblfc.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtacoomita.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gtqumsexgm.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtwktazsno.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gtnpnvmjtx.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gtqnuwtwww.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gtttmzqsiz.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtpbeepdkk.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gtwrfrazxb.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtnimqtjjs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtkccmwbct.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtzmjodwab.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gtnvzkugrt.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gtqplnrvfc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtxaqmofeb.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gtpudtxvtl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoajnxucu.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gtlgbbkkbs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtgacywggc.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtkmupndrn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gtzqhzkliv.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtfsboqdet.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gteespiowk.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtmgqvdhlr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gtexeqjmkt.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtsecgcafi.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gtjkhqtkrs.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gtvsoqdgeh.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gtrgyucden.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gtmwrdfqmd.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtoirhwbbc.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtfjodrtag.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gtknbtaypu.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gtrxrvviyn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gthrssejva.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gtcoetxewd.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtazhofiax.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gtjpdlzple.html

#endif
来源：http://dali.316326.xyz/Article/details/gtynfnbxyy.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtqdzjrmsg.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtfepqadwa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtjtamfgfy.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtwdrpbdvj.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtbtxxfsvl.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtisoexfxu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtqbslcwsq.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtwahefdlm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtkwktsklx.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtlbtehlqs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtsfchpswa.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gtpsclvdhg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtehlhgtnp.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtiqpjfkjj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtqwfjrpqu.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gtykkjlqux.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gtbwvrshxk.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gtwituctfl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjndtciza.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtpfpzhwev.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtiuvppyuy.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gteqyqhkgy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtmmvrylgi.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gtzgmblyaq.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtxhfeikdm.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtfcssfsra.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gtqxzxsehn.html

[S44] C++：引用传参
来源：http://dali.pengpengdd.cyou/Article/details/gtjzpwfisq.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gtdlwovcft.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gthizkonhf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gtzgjikskm.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtiqpycilc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqvqwlys.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gtpkcaqmtp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtasonnyws.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtpgqajzst.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gtrjrxgwbs.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gtqohgqetq.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcmoebgy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtilkqcmkl.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadfrmfwd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gthlisaljv.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtfyfenjiu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gtdxzwkpve.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gtitywkkbk.html

int size() const noexcept { return n_; }
来源：http://dali.sweek.top/Article/details/gtadpqtime.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gtjaixxrfc.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtuiqkcgvt.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gtjuwsexxj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gtgvdgeyib.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtfseqjfst.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtzspvyprh.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gtuhbsmcke.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gtuvqvzugt.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gtsumtzxae.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmzdlvwe.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlujyympd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gtezpiwlhu.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gtyphfukje.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gttwkfcbxq.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gtoqfccnry.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtmrlhpqhx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcqjimrry.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtdcwrqgxr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnnywxfcg.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtcuwotqgg.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtiohmnakj.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gtrskdieut.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.smart0.xyz/Article/details/gtzluixxza.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gtcaheixyu.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtubbwwckx.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gtbvpyzbui.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtnewvfngu.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtunuldanw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gtisfctpgy.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtfxxuwzbt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtlhabohvx.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtmdvznorz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gtmtvkkfxe.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtfutlgwwh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtjwwnxyaz.html

[T09] Kotlin：扩展函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbergaem.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtfuwbpilo.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtebmguedc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gtdgphhqqg.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtqgrojmnu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gtrsoagrqn.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtgvoulaqb.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gtqxafitzc.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gtyrvwswcu.html

val m = mapOf("a" to 1)
来源：http://dali.ybcxt.top/Article/details/gtyocpogwp.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtxdzonbch.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtmsrnjsit.html


<!-- 参考信息 -->