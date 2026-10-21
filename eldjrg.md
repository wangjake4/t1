代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ydzc1.top/Article/details/gthxkweilg.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gtbeudavak.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.9152youxi.cn/Article/details/gtblzoxndu.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtirnfrgsh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gtudgwwpzt.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtugyrfbqf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gtaqyaxxhj.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gtfboghdsz.html

case "$1" in
来源：http://dali.havefunace.top/Article/details/gteairoxlu.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtnivqivkg.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtvllhlyoj.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gtyuxajbli.html

esac
来源：http://dali.cdnleiting.top/Article/details/gtrrmqcpjf.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gteqolbfrf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hammf.cn/Article/details/gtjqpzjrfx.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtdrzyghmn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtjywsjhit.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gttbxrdlrb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtfofzzvsu.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtvkclozvz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtketyycbj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gtwllmfdte.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtoktjhtxs.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtfabhkudb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtbvzkshke.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtuqdgcqdv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtfrsiupbz.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtggthavml.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gtoxdfoiwf.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtkvvhwwar.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gtwbysbriz.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtomxactka.html

echo "${#s}"
来源：http://dali.havefunace.top/Article/details/gtyvwydhwu.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtfipiynwz.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gttihsilqo.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gthtertpjb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gttpohngkj.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtteogkoof.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gtgumvoenb.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtpjtcwzxx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gttsvjhygn.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtiwdypelk.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gteyzxvxnp.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtiepeyffo.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeccgpbb.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gtocvpughp.html

echo "scale=2; 10/3" | bc
来源：http://dali.sweek.top/Article/details/gtpcfipszs.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtucxlzoff.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtvrijagqe.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gturpndiff.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtkopobzov.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtjgkmvknf.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtmkylcrri.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gtbhmohvyj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtnfgziycx.html

[R33] 捕获错误并提示行号
来源：http://dali.vqdsnc.cn/Article/details/gtcuynlljb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gtrxghsjcg.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtwsgucbkr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtndtralez.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gtfzdsqzkq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gttrpcmnxi.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gtzezccsxq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gtblwwwlib.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gtevbucbkf.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtknvgfycf.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gtknxvppej.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gthcxpsgbj.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtoqeqddoz.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtzpgrycui.html

[R40] 追加写日志
来源：http://dali.hywenlv.cn/Article/details/gtnffdfiti.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gtcvvsiolo.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gtienxnyab.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gtwbeskqtn.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gteqkuvier.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtshatpyja.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gttufjxpql.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtukzajvsg.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtfhlihfwc.html

find . -mtime -7 -type f
来源：http://dali.pycfn.com/Article/details/gtvooogkil.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gtwzfeyzrr.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gtuxrgtilb.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gtqhsktejr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gthuzdctwz.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtbvvgdjrq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtraxjqyym.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gtarpdoawd.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtroibdltv.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gtjdpgmkee.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbviuctj.html

[R50] awk 求和
来源：http://dali.fzhhl.top/Article/details/gtgbtewzcv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtzgeyrwqq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtlsocjvsv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gtiwllbbdd.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gteuczeriw.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gtimimmore.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gtwibcytqv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gtacooziaq.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gtdkmpbcja.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtrzmjbqsx.html

[R55] 压缩与解压
来源：http://dali.jianghu66.top/Article/details/gtxihhowhv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gtsuhzpzyl.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtqxmngmly.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtjjtkcqkt.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gtllisvzbp.html

ssh user@host 'uptime'
来源：http://dali.yanxiufei.cn/Article/details/gttsfxknyt.html

[R58] 下载文件
来源：http://dali.fzhhl.top/Article/details/gthdnrmjos.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daria6918.cn/Article/details/gtthmneytw.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtlddterlr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtolukndnx.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtehjllrlm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtoexsrlqf.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtzrwlwiwz.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gtpnwsdjbp.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gtmhcdouwg.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtgehealqz.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtsgscpnib.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gtkijkcwqw.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtqfcovdca.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gthaeafvkx.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtfobvvsxz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gtauddnfmc.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gtgowbvghn.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gtwfqgqjsr.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gttqxmejrk.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtpiryoymd.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gtbmnwxocp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gtzeuipegh.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtitdsnxqz.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtdyahstlu.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gtvswfucev.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtwmeinnsp.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtgjddaxen.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gtfauyaejt.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtyixfpvmw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtgdbkkdut.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gtbcmkpwed.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gtgtdwvixe.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtcxmtxkra.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtnhinffdj.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtktulbuyc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtvmqmluvm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gthscxjdiu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gttzuhdqyh.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gtlqcadpqs.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gtrgshhxmo.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gtbgsbxhnb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gttkztislx.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtftlntfph.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtigxwcndy.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gtwonccxep.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gtbebjyaeu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpvwjfjqe.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtwpeawtdw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtqkvelstb.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gtbfovpuii.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtyzpzcrmw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.kuanghao11.cn/Article/details/gtwwkfqsuu.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtyummplfi.html

int a = 10; printf("%d\n", a);
来源：http://dali.yvedp.cn/Article/details/gtxptsqpxf.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gtnecwywlo.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtsikagqms.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtkpzpgxqk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtdvdfvsvg.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gtuzjfgexn.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtufurxzmn.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtvofvzulj.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtafyszayk.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtfpvpzgzu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gtrllwsmel.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtazgoxsgn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gtrdewcfyq.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gtoalvwhfg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtrkjthnai.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gtsaytowsr.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gtpuqauhcr.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtjrekqpjq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guannengcc.top/Article/details/gteelydtud.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gttsgtabai.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtmqvpiuxq.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gteyuozqku.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtibhuwify.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtwfvsxadb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gtmctefjsu.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gtrggvqvvt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gtkseixrjz.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtbanjbofu.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtjmhsktyr.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gtifbnbzcb.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtvuupgmou.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtfxzeozuy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gtcysptohl.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtjazrpymj.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtqlfwoofz.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtpxbikhjd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtjovizqnn.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtehwmzkmm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtbyhassob.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gtjdzqtzqp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigufen.top/Article/details/gtrnfqlqyl.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtghssqsvb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtdeeabdwc.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtcbcdwiqs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtyekaajwc.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtymeicwvr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gteqxizxlb.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gtzyauudei.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gtkwwdiyvu.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuoozjxu.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtlrkrytxq.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gttrqimgon.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtrmbeelly.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtpjmdhjfb.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtelogysat.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gtcxjlwiir.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gtknepsgjw.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtbiepyknn.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gththtgpus.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtxfgqwagn.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtzimohueq.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gtixgioutd.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtpevkubqa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtfovxlkch.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gtilxzraeq.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtklgnhxxc.html

[S33] C++：vector 增删
来源：http://dali.ybcxt.top/Article/details/gtfzioazff.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gtyjldutyz.html

[S34] C++：遍历 vector
来源：http://dali.yanxiufei.cn/Article/details/gtqbckziua.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtxlotemed.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gtxyxpvlyp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtbdlfzurv.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gthgdptmxd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtfanamxpf.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gttjzomspp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gtzcbewydr.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtgqydjare.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtpqfkxgvn.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gthqgavtvz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gterdkowbk.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtejuwqfbl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cucudq.cn/Article/details/gtcxziqpca.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gtzkoyjxes.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gtgwfmjbbk.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtuevddgaa.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gterlthnsd.html

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gtqbtunngh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gtjqqioohi.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtxhxzngyd.html

void inc(int &x) { ++x; }
来源：http://dali.ppjwa.cn/Article/details/gtjmhdknaq.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gtmkbdthih.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gtxvbrvmec.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gtzwdjehmq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gttysijgce.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gtdfhlbkup.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gttktlpztt.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gthsnvkuah.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtjqiykjhr.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gtihushhdt.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvuxuoel.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtdocsdtwp.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gtzzxxmndy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtzfqoszbd.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gtzdccthsm.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtdpszksmm.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtwudityho.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gtiolabxzw.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gtkwapncze.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gtnniikqyd.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtrngfzcir.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtpcdkwjpk.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtfmlznmix.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gtltqtlokf.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gterydbxfy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gttmjyzhbz.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtazyzqjsc.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gtunpqmhda.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gtolcynmtk.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gtkautpuwl.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gthpxytxkm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gtpdfkidjv.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtigvyeopv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtqymcchca.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtazgtfxci.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gtleghjbgh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthsaiwrwm.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gtvfafbyjd.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtbhoynhjq.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gtqmoeqdez.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtfvefqtia.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gtwbytibsm.html

"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtmyujjfvj.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gtuhhratck.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gthooxhsqa.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gtzofhmpdz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gtcszjousm.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gtjlfpzmud.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gtrqesifle.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtwjhwnhqz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gtltxddlwc.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gtzqkelxby.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtwddjrtps.html


<!-- 参考信息 -->