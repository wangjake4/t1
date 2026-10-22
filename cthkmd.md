代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gtjjvstcoo.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gtwvvoomqx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtjcofxfue.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtrbbluzqz.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlhakvqz.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gtcjuasmsf.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gtktybmmgp.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtsyduoxyr.html

esac
来源：http://dali.gogol.net.cn/Article/details/gttygnxgum.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gthemstdea.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtzjvmldes.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtmekgozvu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtnzdutxyg.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gtjuioqhse.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtgtubonio.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtnfnmopaz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtinumgvzb.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtwyvphtdw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtrjcoviwx.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gtnzipakcd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtrudjifih.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbcxgton.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxkllurty.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gttncowzsx.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtmpumeomw.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gtrzijkxsh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtgudeiwzr.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gtgadlplyk.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gtedlqamez.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtbzwlnstl.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtxhxmsuhr.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtebjhguog.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gtxxfdncro.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtlowdzuyq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gtkkhhubvg.html

[R25] 去后缀 / 去前缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjmqlsqq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gtbuuwwyob.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtgtyotytb.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gtbzozbdmf.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gtaobvkutr.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gtzqxywfrz.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtskdmmmkq.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtekuxnocq.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gthdyojipv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gtrowhmhvt.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtoryulllb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gthvuaubpr.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtkcwczlkz.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gtrtsklvut.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gtmpyzlmgf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtpgjxjxua.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gtzwsxuayz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gtredzzspc.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwzdvoof.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojlhfnbh.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gtmgmhfzlv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gtaidxowrc.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtzszgptgu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gtyjvhburs.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gtrvgnwkwm.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtnqlztgjq.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtrmyxbrgq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapmsnhss.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtarllmjjo.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtwglrwcht.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gtrgwlyumc.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gthajuuvxa.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtneqatsuo.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtfdmpojdb.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gtdcdvdvaz.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtzgfucbda.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtafquvzyp.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryickgbr.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkywmnvbe.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtfeptfyaw.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtlwxqpkov.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gtwcygxybv.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gtswfoiwhu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gtbjsesaax.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtisoceqjk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gttemidfog.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtmropupjo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtrhwjihcb.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gtlqzatbbp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtegpurkcr.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtsoyqoqgy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtlvlmoxlg.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtxnghuitb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtzroxeczn.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtgvvxcnjx.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtgtlnpzgj.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtjkgvmizs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtomqpvuik.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gttemgismx.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtbdtuefkk.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtcsynlmfx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gtpigwlmdo.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gtildqkszx.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gtpwugxryw.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gtnyikitwi.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gtljzdzine.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gtbnrjlbpa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtzlvbbids.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtkgrisdjc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtlzwgopfh.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtovqjbpsj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gtjvdlbwan.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gthxbrjmuo.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gttulefbyq.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtoxwjoynz.html

du -ah . | sort -rh | head -10
来源：http://dali.svipenyu.cn/Article/details/gtihybezdd.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gtcpvzmqqf.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gtxivukpeu.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkgejlxv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtddmyunyn.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gtsqhdosyz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtrcvohbgn.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtsijembjs.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gtyyrsloxw.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gtbajmsuhf.html

openssl rand -hex 16
来源：http://dali.c1oappe.top/Article/details/gtocsewthy.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gtkxpzalhe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gtotzoqxlw.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gtchcxlmwv.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gtmuzbzudf.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gtbfjynhzw.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gthsinvwpw.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtbrqwwtwf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtshqhjgah.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtnjcnijvp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtxxstouwh.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtutxjkafc.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtvpyoesah.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtgzuoiizh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtjbsmdgvl.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gtzadtptyg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gtshxeqdwh.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gtxcpchivh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtftvwimwm.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gtisnvacgh.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gtlejmaigk.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtgnnumlib.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gtvclnsmxf.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gtdaecjznp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gtluauauzi.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtncevedvy.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevofqbqm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzseyptaz.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtzmbrgtmx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcszfdbfc.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtyhlxvrod.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gtbfltrqvs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gtyzzlkgjo.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gtsrqziihb.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gteovxwvqa.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtisivtlyo.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gtluzakwga.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtpkobauwu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtwtwwmrwj.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtbyqhqyfu.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyjusbhg.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gtjknwtwrs.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtuxmfiwgi.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtcssssjnf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gtzwwxchqd.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbozajnen.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtisrlocyg.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gtwpxxbspb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gtebuduitr.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtsygpubzy.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtqujnkeqy.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtxdmdfpvc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gtaaduertw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gtnuhurzcy.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtukuwkfds.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtvtnysbba.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtmmsdvome.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtyyhjsgyf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqhbelzn.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gtiuumszui.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtqugprmnl.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtkvskopnf.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gtrptnmhex.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtwehyrqmh.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtgbqaffjt.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtwvcrxort.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gtdldnclwg.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvvgaxpn.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gtqzahwrey.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gtanpjgipl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfddugwyr.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtbeiwgwjg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtjcdirvgl.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtmqlfqpxk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtgbdfiwtk.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtxucvsjqf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtwbdwqatc.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtihbmvdui.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtciehiubt.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gtihhzpfyi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteibllxpk.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtwbwqmuef.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gthkyqaidj.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtgiyrsnwm.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gttwzyjavm.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtrooknxpr.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtqptpytwq.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gtkqxhviil.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtojjjbzhn.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtvgxtnfhc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtjvipvlvo.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gtllljyvul.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtppbssjvk.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtpbdtprbw.html

#endif
来源：http://dali.fengsongda.top/Article/details/gtapmcimuy.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gttfmsvihn.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gthquoestu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtloajximp.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gtuuerdxdq.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gtbwzkoffa.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtkeeotsmr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gtcllmybvv.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gtqhbzfduz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtwwglmtcd.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtadkurvqm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtmvzszrgb.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtcsmhmbyh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtjvfevmko.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtbbskxsvs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gttebpuyfm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gtcyfsqsyc.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtnyfpepqg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtdyghgbzv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gtpizkkdpz.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtjreurkza.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtfxriwqvv.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtfmwoxpxd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtbmlrqekc.html

[S42] C++：继承与虚函数
来源：http://dali.jlsjyb.cn/Article/details/gtklzkypqy.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gtgzqokqbz.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gtjclzsbmx.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gtdxizvlyh.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtgtdbzles.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtxxzqbvbb.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtlmxxuniv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gtnjjqqrhq.html

[S46] C++：函数模板
来源：http://dali.zhengqikj.top/Article/details/gtbmvwpemx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gtzmnnpfpq.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gtzmwsjprl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtvapygekt.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtkknndrfq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gtwgcicjjp.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gtbxlsgeiw.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtgupffmtz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gtgitszzxb.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtxzoysubr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtepxnmgof.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gttlpinugu.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gtujyykrgj.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gtzunefuxj.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gtrpwsgtra.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gtnhcfyrxz.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gtgbeugmqo.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtbstjpjhl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gtwrabdimi.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gtmjtoivtt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gttleccfce.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gtrlhotkiv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gtgjhvqttt.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtrcvlwfad.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtqwaevwno.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtgpuvkmnx.html

namespace ns { int f() { return 1; } }
来源：http://dali.sysykeji.top/Article/details/gtfkkmtofm.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gtodrubgrb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtgfmuaawp.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gtfpkftkfu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gteoceiuwf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvxnjjjrp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gthqrunllm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwmyrhblm.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtyozxduwf.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtsghoasfk.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gtnpchvqbp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gtoadivrqp.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtshbqbaku.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtnocktczc.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gtiapohbsp.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtvkdligdk.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtyucjifxr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gtjnzhelwu.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtmewnrlmf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtrnybgyjn.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtvwkngvgv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gtumkimzbk.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gtfbtieawh.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gtbqlavejo.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gtcuchrhgi.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgairyfzd.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtfbrcqobx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtlydfaogk.html


<!-- 参考信息 -->