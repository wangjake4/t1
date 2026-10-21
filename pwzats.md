代发 wailian999

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gthbnptcbh.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdpwgdmy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtmgowvxcg.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gtjnzeuvbj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gtywrcuziw.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgulbgod.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtdunkibnv.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtbtfvppiu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gtjnzitgzb.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gtdjfgtkex.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtuwxgdmja.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gttiyzyozl.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtvfvjcjvd.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gthnotvgny.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gttqhacbkk.html

*)     echo "未知命令" ;;
来源：http://dali.meibo888.top/Article/details/gtubtassty.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtovwnsdah.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gtevcgcdog.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtjxvvxkmf.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtehlvnkxc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetdadshb.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gtjtxzhaea.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtplrwxgyg.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtqahzrtpb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtyozgbrfp.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gtksverpnz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtihxwnjdj.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gtnoarbqrh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtlqvijajh.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gtcgzxaecl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtfrvdypxz.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gtrqlutnmg.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtkmwephbg.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gtwvdbvyir.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtblhukaew.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gtybkgccpk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gtroymebdu.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtiejqjlts.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gtuatxxeln.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtvilpwkiu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwwgozvw.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtccdqzeue.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gthzuoqggo.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gtbufetoxm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gtdjaehvcx.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtxdcvvjci.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtscgwxlvv.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtmfytspjv.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtklanevgw.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtcglorqfy.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtfydjcada.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtoqkoccqf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gtjrwnmrts.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gtwbkwdcsp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gtthtfdrgd.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtbmciztkp.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gtgwefkstl.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gtwxyxpanf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtdbosbnol.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhefwpkm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gtuqgocepr.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gtyhfgnhdy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtasvgmpmc.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtmtnhaxxk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gtjmfvhdqx.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gtnpvpyfrw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gtcfmapgzk.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmclgxwl.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtlmngmptl.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gtvkyauhxk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtdjvwkmnl.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtnjioyfwd.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtykpqqrur.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gtxrkhcqkg.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdarnzso.html

[R41] 丢弃输出
来源：http://dali.gotoacloud.top/Article/details/gtdyazvohp.html

cmd >/dev/null 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtzzhfyyce.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gtuwjromjd.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtorwwqamn.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtfzgzyitw.html

find . -name "*.log" -type f
来源：http://dali.yueranfly.top/Article/details/gtjrmjqkgp.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtmbaumtvt.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtknbhiyji.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtcakoocsv.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gtfpttmsfd.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtawslaavd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gtmdckqnsr.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gtibrsbypu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmhgxcqd.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gtyhoqfepy.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtklgrnjgc.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gtlqcwxvxt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnphfnevi.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gtiraedrzo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutxhxqnh.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gtttkensvj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gtalhdnxlc.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gtsmgkxyie.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnubucnc.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtzfeuoshz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gtrtbhxvdb.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gtvqiklgel.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtrnclojtz.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gttawxepln.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtdptziktr.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtbctazniu.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gthiawcpid.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtbexvouxk.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtkmoasovh.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtspinxlgx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gtarzsjoby.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtsmvtishq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtdyrgyszx.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtwhmhahrd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtjdqmwxpx.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gthxvcpiak.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gtguajlazf.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtcyjshcqc.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gtnndzvhet.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtfifrehww.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gttprwbdlk.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gtvlsutlue.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtqpqtznzz.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtwsstjgii.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gtrqjmbpax.html

[R66] 定时任务
来源：http://dali.nanxinkj.top/Article/details/gtiyecyuel.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gtoufkbwum.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gtxbkremrv.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtprktnkdu.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtyaawrkee.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gtepysioxr.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gthfypvqnc.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gtcomnrkjp.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gthaddzeqt.html

date +%s;  date -d @1700000000
来源：http://dali.wangshuangyany.cn/Article/details/gtoqrvihnx.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtxemoakas.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtpoepiyql.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gtbyladiqg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtvkyidfqa.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gtpcsuttnf.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtaikoiqve.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gtbjdpqbgw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gtwkeaqqmg.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtsyzjauyc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtnhseqjka.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gticrbpfix.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtewhbxjoo.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtiqanefcq.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtcqyfhgye.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtayagcwgh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtgpzhmrac.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gtqxqfbgck.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqssdivw.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtfwbmquev.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gtzqcbmkiv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvxxozfub.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtxsiuewzz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtnqtrolic.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtxmcftccm.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtsnzrmdsz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gtcdpenfhq.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtfdpvpqkt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtjqdksdll.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gthjplscmz.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtzpfdqodu.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtmlrwxvxj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.andypj.xyz/Article/details/gtlxkpxqii.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtdznxzkpw.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtgcvvaola.html

[S06] C：字符串比较
来源：http://dali.yvedp.cn/Article/details/gtiepepdcq.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtmpuyexcd.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtmjmnarco.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtmvupkswp.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gtvydstpar.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gtjiblisgq.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtmwqwmhfa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtxurhxsms.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gtcazylohe.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gtmlqoyahm.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtqjdpnvkj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gtuirajstg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258888.top/Article/details/gtxxdtjmwa.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtpjjkkoge.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtjcoelupq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtcshuruux.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gtwvzgccml.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtoxjeoygt.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtdfyapbux.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gtkzxprbya.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gtlpqddjdq.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtkwimzzyk.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtbkhqnqlh.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtoqihmznu.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtakngtghn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtzaaixosz.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtxozelxqr.html

int main(int argc, char **argv)
来源：http://dali.jiagoushi.top/Article/details/gtixnsxlfp.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtxnxxndmr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtqewvvxce.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmmnrcpz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtxfqbtwop.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gttxkzpnmn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtafgfojsv.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtheokppaj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gtmwktvdsa.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtgptjbonq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gttmnkongd.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gtgtgktuij.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtxwmobkrx.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtckeiovfh.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkcaasjz.html

[S26] C：内存清零
来源：http://dali.pycfn.com/Article/details/gtzdkbldhr.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gthzpxwzcv.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gtsmikkrny.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtloobuaxt.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gtldffwvoe.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gthljeufbb.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwgskfnue.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzzqiipv.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtaubrmxhq.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtnmbpgwnu.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtsirvbkrr.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtgusmfekh.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gttfofnfuw.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoizklhn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gtwuhwocwp.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtjytwdtub.html

std::string s = "hi";  s += "!";
来源：http://dali.daria6918.cn/Article/details/gtenwgmojl.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gtmwbzefwo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtbxgyaupc.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gttksvclgf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtzyodnlyt.html

[S35] C++：map
来源：http://dali.chenzaomai.com/Article/details/gtxwkiitgw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtmjznmede.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gtaoiexrwa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtpqtnkurp.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtkucnvzzp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtlzvnsuxk.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gtgdgvazxs.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gteefadpgt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtxzdnesaj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gtxbsawceg.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gteywgrhnm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gtzvghxjrk.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gtbhobmxpd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gtppnwhbyg.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtduvplcjq.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gtgwdvzymx.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gtpdyeljus.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gthrgwhvog.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrklkobag.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtavtpaitg.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gtnleqezkl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtenimehnm.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gtzikegjsk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrohpcgxj.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gtnzkizpab.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtajvihndf.html

[S48] C++：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrcddfbid.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtfaivdbgt.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtkitzhbfk.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gthxvxtubj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhongyouzk.top/Article/details/gtwyiamqjq.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtwqxglhau.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtepwqghcd.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gtnwmafscy.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtioaytorp.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtgiolxuhj.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gtttrauvjh.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtgnnwybjc.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gteoaietkj.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gtpezfsgnu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gtnwduwrtn.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtqigtettc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gteavfocxp.html

[S56] C++：optional
来源：http://dali.jiagoushi.top/Article/details/gtnlyfxryy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gtrwjoltuy.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtsifycrxn.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtkbxxydto.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gticgxcsyg.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtyvthdxix.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gtxdunrcmi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhongyouzk.top/Article/details/gtlthllkpc.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gtdbomscdc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cheryme.top/Article/details/gtwhoqlbwg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtcxwcnukq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtrqsvufvx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlhaxiyee.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtfrgaitsq.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtplcpisuu.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtecchnzkw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtmghffsxn.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtglgyudak.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtfxdjqlvu.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtkmiqlwll.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gteakkajqe.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgyzwpzb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gtpioceqgm.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gtcasflssn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtujsnxcnc.html


<!-- 参考信息 -->