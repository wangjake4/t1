代发 wailian999

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gt2olheldjh.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gt2evbadogz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jfwsbguz.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdcqwllm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gt2aoszlwzr.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gt2cusorghq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gt2cfsytjxs.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2flcwamzy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2hlltpdyh.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gt2ddlkilsf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gt2scfsssqp.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gt2mivylvow.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gt2diarvjvx.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gt2ruywqehe.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gt2veylmvho.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gt2enezisvv.html

esac
来源：http://dali.tanke756.top/Article/details/gt2bogaoejq.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gt2cjbbnzto.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2bbqlseoi.html

[R13] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gt2sbgsdpfw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gt2dpvprxfs.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gt2yzkkclfm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2fzsfgmjq.html

[R15] while 逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2jlkgvqpr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gt2mqanjojg.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gt2ryevhunb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2dufigyxy.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxcowoyh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2xocbfphp.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gt2qwrujxgr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gt2annyserv.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gt2nunjaldr.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2hsbfztqh.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gt2unyotzxr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2zjwhlkat.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frlorgbc.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gt2pxldlmoa.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gt2zqhtwwtj.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkdircdc.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2ucwezrbe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gt2yvslaalc.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gt2ciunexua.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gt2ipxxqlhp.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gt2lfbdosje.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhfmwqse.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gt2abjdnbod.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gt2wuubvxii.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gt2hznifbca.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gt2knuegjsa.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gt2cynynmyv.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gt2bmkyldry.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gt2kpxlkkdh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gt2mihiufle.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gt2rffxsnvs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gt2texvqiwj.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gt2yjvejkpk.html

f() { local x=1; echo "$x"; }
来源：http://dali.xinyue.icu/Article/details/gt2lxudlukg.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gt2dhhsqexe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gt2qgliyqli.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gt2noxzehxe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gt2zjvwqepc.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gt2tpmujlxf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gt2zybtkcns.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gt2wtwmaosa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gt2bziwrnat.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gt2mldexynl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gt2nteglkvz.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gt2ldqfgdhj.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gt2jxvfkgcs.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gt2sracpymm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gt2hoahuobi.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gt2jayiyvjz.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2qfwzgozh.html

[R40] 追加写日志
来源：http://dali.sufxvd.cn/Article/details/gt2xiscfxve.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gt2rugksgur.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gt2axmoazhl.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpaooloy.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gt2fkwusgwe.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2gedjcokb.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgnsjrli.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gt2fewlbwha.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gt2rwuwveoe.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gt2qtuqnzpg.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gt2yksrdxdi.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gt2hggtshyx.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gt2syujxdyr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gt2pglvhwzb.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gt2gnheftjp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2rrmnrglq.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gt2tcfdfxjf.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2skummysp.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnswgqjt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hysaishi.cn/Article/details/gt2kngmmivx.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gt2pstquqdp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2bzkuwrpo.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gt2gmdsicfm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gt2szoskoed.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gt2jmzsmlew.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2rweqlskb.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2lwxhkrcd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gt2qnxckgzu.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gt2gtzwlsad.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gt2smebpkmf.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gt2hiskiohn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gt2pfifemup.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gt2dbzrhmpa.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gt2nhoglcdx.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gt2pmkvjwju.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gt2tkfzqekk.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gt2yqueggdg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gt2wvscitab.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gt2ivvklugw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gt2txeaqrbv.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2eiyirhug.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gt2ezhifwhr.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gt2cfoyxgxv.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gt2bmqxswiw.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gt2oxhhfert.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gt2oiyfpaof.html

[R63] 内存与进程
来源：http://dali.yj20258888.top/Article/details/gt2lmgnrceh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gt2rimwoptp.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gt2lmqlrmye.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuanzhike.top/Article/details/gt2gqwgmqnh.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gt2clyphduh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gt2duyzpkwj.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gt2fjewzvps.html

crontab -e;  crontab -l
来源：http://dali.guannengcc.top/Article/details/gt2jrtbwigf.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gt2zhrzrdsq.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gt2bocfpsha.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gt2rmwqtltq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2srtnjhcb.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqspelnb.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gt2dwptgqhc.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gt2xgogcrok.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gt2dyczmdce.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2stlnmgrp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gt2bzuopdzq.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gt2ujwqleyv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gt2etycslva.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqveclpq.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gt2bapfwaom.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gt2pzlbxuux.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpcsytmg.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gt2cjndbdng.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gt2fpvxhthg.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gt2vufisgag.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gt2ydfkunrk.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gt2ylxejzmj.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvyocqfg.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2rzfifdec.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzuaqqjn.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gt2cjmqmkjl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gt2vqzwtdsh.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gt2jurubazz.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gt2dbrjuwyb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxymgjfj.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gt2bppjxjiu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2kottlxxg.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2vnvkeenw.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gt2gaviwnai.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gt2voerbudr.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gt2gndwoimh.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gt2ebixdpje.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gt2bfvlblgp.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gt2oakfsyip.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gt2uaccjnpr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2okjsgdwx.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gt2mkgvhsgm.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2vyyimlii.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gt2tyuupkyl.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gt2ydtdyhhl.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uktgahnx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gt2omwympko.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvwkvdkl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gt2vkwmnimc.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gt2sklqfdsl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gt2frpgdkup.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gt2jezsvkui.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhemdpot.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2kipmthqd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gt2jqbbmnal.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gt2ksvpxase.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2zyawqcpp.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gt2xwxkzdxq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2jxtdtsgp.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gt2yexgwufl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gt2zynpiyai.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2rwtrrqnr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gt2slwrmqby.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2whxvikre.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gt2qwhjhpxu.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gt2vhbtwqys.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gt2qlebexlp.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gt2ojfzwamu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gappnlik.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2ogdviktf.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gt2yhjqhcdc.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gt2ijoionye.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2wmplldxm.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gt2wvhepcgg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gt2mpzdisij.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gt2zvtcuwzi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gt2abbglccj.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2oflmxcmy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gt2biqgjvic.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gt2nzcdoyco.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gt2aucoullg.html

[S24] C：获取本地时间
来源：http://dali.xinyue.icu/Article/details/gt2xdhhikiz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gt2sajjlbgz.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gt2ayelmjht.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gt2nhahbiet.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gt2zpwosmgo.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gt2oabodbzs.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gt2aiiqwafh.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2nutcvaef.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gt2ctzhydbt.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gt2eboovrkc.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gt2cdypaibt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gt2maezptet.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gt2nztwicgx.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmsknggn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2caqziggi.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvqcmlao.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2eblqlpgv.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gt2umshrtwo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.smart0.xyz/Article/details/gt2dgpbkbfi.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2uxxwlxsu.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gt2txvmcwzk.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcarmmjh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zousgsee.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gt2kcdulton.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gt2mskomjbo.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gt2crkkxvwx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2ygztqlbf.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gt2aehklagd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2wkfajqng.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gt2eljnuwcd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gt2jiqctsfl.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gt2srozypzk.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gt2fpwohtpq.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gt2rxtcbnff.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gt2boxoahud.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gt2zpqtftdh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gt2ybfjvusn.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyslczia.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gt2iiyhveef.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gt2jukxxtxz.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gt2zqldejgc.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gt2twdrsgqb.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2wkcuscgv.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gt2bmovfmcq.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2oxyffime.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfwwudhz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gt2hmuxydzi.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gt2zwiiazkl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gt2ixeflzah.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gt2qulguuqu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgrijagn.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2qvdkioyi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gt2bmxpqcww.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gt2aitbqzug.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2fkbqtyuz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2etvwttel.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gt2dtsworft.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2otdhxbvx.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gt2yraidmuz.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggwegivz.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gt2udnmvmoz.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gt2wneiokzh.html

[S53] C++：移动语义
来源：http://dali.jqgfzy.top/Article/details/gt2nvimxete.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gt2qsbaozgt.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gt2ppalbhpf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gt2diggavze.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gt2qtqfdvek.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gt2pnupyuuz.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gt2shlccvec.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gt2wuzxypcq.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gt2eazzrhxn.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wolbqwvu.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gt2vefkmbvn.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gt2scfmybxk.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gt2urimlhme.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gt2dnqpknru.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2ttcgxazh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2shmtzgio.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2cjsqdifg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gt2zasprupy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2byhqliot.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2hmwnoskj.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2sdvyjseb.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gt2yevhqcdl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gt2hyhozwcg.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gt2mpqkbczp.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gt2arochtzi.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gt2lsrawbqp.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gt2vbsogpmq.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gt2ynrqfyxj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gt2ubiqziax.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gt2cnzdwuax.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gt2miesixbo.html


<!-- 参考信息 -->