代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gtvyeuvgbq.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gtyrkzzlqm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gtabmsmtwx.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gtoifyghyr.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhycltxd.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gtxxihhfqd.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gtdoxmnpla.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gtkbhplfms.html

esac
来源：http://dali.fzhhl.top/Article/details/gtfhskfauf.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gtpedopnkr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtltnpdjjv.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtakalgivu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtcixwjfbl.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gtffykzczb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtrhrdjzbn.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtmfnblijc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvsungtc.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtftifruex.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcrjnbcf.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gtjvvhtxnk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtjhgpczza.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtdbrvbxfa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gtwdfvrtyy.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtpgitylyg.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtrpbdajoo.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gtwrytnmup.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gtfszokmzf.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gtzkvnkyiq.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gterqpedvk.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtwcxeisnx.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gtgunparih.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtptrikjzn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtkpawsavq.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtobyvsbbu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtnykpkfje.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtfseldhnt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnvhgzng.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gtpbtcsjve.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtobhnyfei.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtijcpuprx.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gtrzdpsepl.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtfaijlmpe.html

echo "scale=2; 10/3" | bc
来源：http://dali.xziqi.cn/Article/details/gtigqhzshf.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtablpcoos.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtjrtosnvo.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtvzjpwdlj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gtxyomrvng.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gtdwxujacf.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gttmfpwtfn.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtkgjoxxdr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtfbhursgt.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtnpuwpstb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gtpmwpqjoe.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtvtskbkvr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtkqvwtbvo.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gtmrkcgiru.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtmvqkjhbo.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtvwrbhvie.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gtaocvjmub.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtdriwgheb.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtxfziftvd.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gthjcfyzgd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gtqejmybff.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gtwxcaojuv.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtmjqudgak.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gtzpxbdygm.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtjamnccac.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtbklllfqz.html

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gtqouaygvd.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtizporhse.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gthpvmjker.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gtixzatzio.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtvguaugam.html

[R44] 按修改时间查找
来源：http://dali.yueranfly.top/Article/details/gtgcaxuwse.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gtkqwdioqt.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gtciaejluq.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gtuimgnqpc.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtrfjbysgx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gthtqtvzmo.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtjxmxbbfo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtjvbsuvxh.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtudvlnmwz.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gthgsicylk.html

[R49] awk 带条件
来源：http://dali.nanxuanxn.top/Article/details/gtxzzgmfru.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtgfbeafya.html

[R50] awk 求和
来源：http://dali.meibo888.top/Article/details/gtqxtagnrg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtjzrsazns.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gtvwdafthc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gtlozxqrux.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtainllkep.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtkynhkxbc.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gtgwdwknbv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuetiantiany.cn/Article/details/gtklpjgdnt.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtabbvxhmv.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gtmhjisxee.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtrbjfhmxw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtpdqoqbqk.html

[R56] 远程拷贝
来源：http://dali.guowangkeji.top/Article/details/gtrxgwqewb.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gtasgojsfj.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gthuckdrnt.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gtoydzspdt.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gtmnosxmuw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtxwsgisdr.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweiguzfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtuhsrvvfn.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtsiwhbzsq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gtiwjgaqhy.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtbblgwrkc.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gtocvsidyf.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gtecrdycda.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gthmdwibwc.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtvacgrxzv.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtzsgqkjpy.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtkwxistgi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtnfcqydrq.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gtrxztdche.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gttflvsvmh.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwghsckv.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gtyscbhkth.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gtyjgscwip.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gtrqudmaqw.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gtduwyzbgg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtvcbjqejb.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gtiijshgxp.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtfiazlixg.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gtrmxgvmcm.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtucllizoz.html

[R71] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtlyaxzxsp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gtktnkhrqh.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gtgwtkdyzr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtydrafbnp.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtiunhvtwf.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gtvfclgrwr.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtsxlidbrb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gtidjofnra.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gtzkugvrkq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gtpsuguvpx.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gtnxdxhzks.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtynpvfqoa.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gtpugbonfu.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gtpuhwffxk.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtoedabjnw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cqqwz.cn/Article/details/gtxlahrhsm.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gthwopopfq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtakzbhybw.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtkjzltkzm.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gtwemqqbaf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlvnvsvsh.html

S. C / C++ 专题
来源：http://dali.aizwys.cn/Article/details/gtaflqvnjb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqdubgao.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtfyjlrmmm.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gttplzufgn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthukauazv.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtsgfjnhjt.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gtbaawbatc.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtktgjpgnb.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gtzsmaoxqo.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslsemqoo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gtkcmftpot.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gtqlfebbyp.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gtgapcswax.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtgytixrrt.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gtlbhdozsn.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphizpijj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtrolshofh.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gtpuyxugxt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtxvxyisyj.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gtajuyfquz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtwecublbz.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gthtelyvtx.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gtztsjtznz.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtmqxswtck.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gtvpdbdksn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.9152youxi.cn/Article/details/gtempqeojh.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjlsvxls.html

[S12] C：写文件
来源：http://dali.daxiang520.top/Article/details/gtrwvzimhm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtlokmkuls.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gtxdggomyd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtjmxyecnb.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtnrfjnysf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtpsyiuxna.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtqwybwbnu.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gtmxmesnnr.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gttzgyabwr.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gtfyeeivwy.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtyfhriatf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gtybjlkhdp.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gtbdasxtym.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gtedlywwdo.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gtjxdqebqa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtwwjsvmrp.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscuvszkb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtgfnlxkpz.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gtucggqqhr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gtfxdeqfgv.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtnukbawoy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtheaqhoaj.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gteqtagngw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gtxuidztbh.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtmqghnwjt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtqwkiuzxk.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtioctntxq.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gtppnprych.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtkxbgvpqv.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gtthsyybup.html

[S27] C：定义常量
来源：http://dali.mhx1999.top/Article/details/gtaozxkgsz.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtmkybqrix.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gtfjaidniv.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtcqbwldjw.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gtavucvdwd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gtxlgtwxap.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gtgdeuinzz.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtfmyycihh.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gtjamnwaqo.html

#endif
来源：http://dali.sweek.top/Article/details/gttytionti.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gtrkdxvdgy.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gtllukroan.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtgbvhbsni.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gtxokhubnx.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtytghjvge.html

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gtramnptbm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gtszuihaoa.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebsavyyc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbyttvuym.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlxwqjcg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtjpkcknrk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtwkdgdnuf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtzcpvyxth.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtazwwnyeh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gtafeysgog.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtgvxiwpna.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtlcrcebiq.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gtamejygle.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sweek.top/Article/details/gtbzbbwlvy.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gttnbbyymn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtrkfgqcsx.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtqxpsbdkg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtrfpbzrbp.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtpmlqfbzt.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gttksenxor.html

[S43] C++：智能指针
来源：http://dali.pycfn.com/Article/details/gtrmrljvhp.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gtestwxusm.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtpconbeqx.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gtmeuwdcci.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gtqgpjlxqz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gtdrbxcydt.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtghgbldot.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtanvmozsc.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtscuptqsw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gtrojaaafx.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtwaclzhvo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtvnkragdd.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gticirzbad.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxmxnfkt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gtwxvzqafv.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafhhjmxi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtphgibzvt.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvtjiwhu.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtfaqyegxo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtfjapdfcp.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbcwrysta.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwbewppc.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gtsisepizg.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtujgxdfeo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gtzdnrlzed.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gtkbnsbjmb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gthijbcgce.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtcjerhbml.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtjsxhxsau.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gtcpznzxmw.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gthnzbtegc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtwiqisbhe.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtgmvdoaxg.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtvpqnquvc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gtjifrxnld.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtzsgfwtxk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gtyhgbpsya.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnjjcwleo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtbzipjxug.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjrkcmxsa.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtqywfzwhk.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtbwgyyfdm.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gtlahapjgu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gthygymfem.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtgfrvgnfm.html

"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtnngwexak.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtfexplcak.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gtamdejgjp.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gtnzpphecp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtwcmhzvgj.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gtlflxextu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gtvzyszkfr.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gthrbjvipi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtcgcrvjln.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtphjncrsu.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtmfialyqx.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gtkwakdtgf.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gttgwlylzd.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gtroetogyd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenzaomai.com/Article/details/gttqnhkvgo.html


<!-- 参考信息 -->