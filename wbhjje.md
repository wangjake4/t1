代发 wailian999

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2nykhqngh.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gt2hlvylfne.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gt2nzawtssx.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gt2ldgjjpex.html

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gt2fvpatjqk.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egqmssix.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2znmntfdp.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrqrsnbg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gt2ueheftkz.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gt2owhmalob.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gzhubu.top/Article/details/gt2jpydopzt.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2wzxuckpb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2noarilol.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gt2ptorssgd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2ysptxqrn.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gt2piidhozj.html

case "$1" in
来源：http://dali.ppjwa.cn/Article/details/gt2udtwgtua.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2mocoyhej.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gt2nntrgqvd.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gt2bbqtljtc.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztaaduzc.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gt2penzithe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gt2qhfpefhp.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2iwrxuxby.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmbllupm.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gt2gztkexxb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gt2oudkakgp.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2ombzwpwx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gt2qmyfguwj.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gt2ertiancd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2uwwwyqxa.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gt2xrbhmykn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gt2tvzepsdm.html

[R18] 遍历数组
来源：http://dali.yj20258888.top/Article/details/gt2hmcmgdmv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gt2zzeyyutq.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvvnaafu.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gt2aeklithp.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gt2zfinvimk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gt2preiykfu.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2qtwhiteb.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gt2ncihcfww.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2zojrqtlf.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gt2osbvjftl.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gt2dsvhmgeg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sxryk.cn/Article/details/gt2jqoqqezm.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2utsfdgjj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gt2nlloenmz.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gt2qsgzgyou.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbmtekom.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gt2uppzdzfx.html

now=$(date +%F); echo "$now"
来源：http://dali.yanxiufei.cn/Article/details/gt2ravzjpfy.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gt2rqckvlug.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gt2gnlmrfvw.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gt2jbnkjldq.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gt2wfjzzrzz.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2osxmrozl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gt2gdmuzpzj.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gt2pfoziftb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gt2glixvltc.html

[R31] 局部变量
来源：http://dali.jinqigfzy.top/Article/details/gt2zwfxyiym.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gt2mzwtdezk.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gt2kqlsezsr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gt2kpphyikx.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gt2yhyxogff.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gt2ikkalyng.html

[R34] 退出时清理
来源：http://dali.bjfxy.top/Article/details/gt2bezcpxgr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2drntgiob.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gt2zuuamhry.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gt2pfyzobtu.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gt2nganrpdg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gt2jvkrwggy.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gt2etwklgoz.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akvjrtxf.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gt2sizcahfz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gt2jyarxrzk.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gt2hbfniuoe.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2wwcgimmm.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gt2xyrpzzxp.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gt2tkabvfun.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gt2mudljozc.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2xmftqjmx.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gt2ekvxupvc.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2cncgmapz.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gt2rppzcpve.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unuduoff.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gt2hhghvvkg.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gt2ksjqokyk.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjiynhuj.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gt2tvrhujxf.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vevhmsad.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxuanxn.top/Article/details/gt2luricujr.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gt2qmjolgrs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2kwmzhmji.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gt2upeaizfw.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2bddzsxjv.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gt2bhycdoai.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gt2eqqelaiv.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gt2fgbwgope.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2kkarmjnv.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gt2rilsfwpx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gt2evkyozsy.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gt2wsptktsy.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgtunnkj.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gt2rrhaqjbq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gt2ffbplgtf.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gt2kchxosqr.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gt2clyswywi.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gt2qzwvuhcx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gt2enlorrxi.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gt2lizwvksf.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gt2mvwigsjd.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gt2linimyhh.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsytmvmr.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gt2aidzvfnc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gt2wwajpxtv.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2nmcqiutw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gt2wqckbtzz.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gt2fjlnakmd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gt2gzvhusoq.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2algbdzlh.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gt2dzplhvdp.html

[R62] 找最占空间的文件
来源：http://dali.guannengcc.top/Article/details/gt2zkwihwxy.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gt2auulloax.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnikvtkx.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gt2uldflxws.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gt2aotsdgeb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gt2bknwvjyp.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gt2zetkixpx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gt2mumjhkjb.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gt2jupzcslw.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyvsucgj.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gt2sgiijzqb.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gt2pqivsdng.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gt2etwbzdpp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2ehrinaza.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gt2jcxbetdr.html

head -c 16 /dev/urandom | base64
来源：http://dali.xinyue.icu/Article/details/gt2dhwyaxaa.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gt2lstvtjpk.html

date +%s;  date -d @1700000000
来源：http://dali.c1oappe.top/Article/details/gt2uljaysps.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2knmxxyut.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gt2nmdyyodc.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gt2bkpbdinx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2dasysgsr.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gt2hdswjzhy.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gt2poeakofm.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfknpzpp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2gplhmgin.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gt2wtdlmccx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gt2luvqvhyu.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gt2eioebfhr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2lfycmuej.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gt2slzxkghj.html

read -rp "请输入: " ans
来源：http://dali.yueranfly.top/Article/details/gt2pobjslya.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gt2qrqbmpwq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gt2rrcobzlt.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gt2yugklils.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gt2tmvnighj.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gt2sagktpku.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gt2qhgrfclk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2cvwvblsv.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gt2yfzncjbr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2iwbolpxt.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2tcmeojzr.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gt2zcfetjce.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gt2plaefaao.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gt2gbpnuqqn.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gt2uxyirvyr.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gt2eckbjmvv.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gt2ywhrdvlu.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfbqgjzd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gt2bfolloja.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2ilvgaqgj.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gt2yiemissa.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2eqssynzx.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gt2ivwcooox.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gt2vcpsphhs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gt2tfnikexd.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gt2vxjdutuo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gt2shxkoxtm.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gt2xnfbqrzi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gt2wrlqzbkp.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqqjyrgm.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gt2wivvjsum.html

[S11] C：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2tqlfrflg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gt2cntfwecu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2ztstytsn.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gt2dbwjzllt.html

[S12] C：写文件
来源：http://dali.xuanzx.com/Article/details/gt2iljoztnm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gt2txigeeyl.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gt2bchujacu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gt2pyquczgm.html

[S14] C：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2icoufwmi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gt2gwhvkcax.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijdtpzns.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gt2nbgfgkuo.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gt2cbhxttcb.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pufrvbbq.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfquhzvg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tian-w.cn/Article/details/gt2rrwhbsje.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbnjqcyw.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gt2lwqvwsju.html

[S19] C：快速排序
来源：http://dali.havefunace.top/Article/details/gt2amsfuuci.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2iwamyosg.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gt2ioayvdyv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2uhvwzhkd.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gt2ujalyijs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gt2lwujxjdj.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gt2suqdledp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gt2cmvskdaf.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gt2npitbpsd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gt2cjlmrvci.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gt2ywmdjrrd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gt2gnncipff.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2wuziursa.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gt2ipktxoce.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cpgfglxr.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gt2ptpkbcho.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gt2umykymtc.html

const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2wnzxopnk.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gt2uwmpswka.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qneehlto.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlwzcqno.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gt2vmoftmbx.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gt2gmktgtan.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gt2tjbjurjb.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gt2hkorcdhv.html

#endif
来源：http://dali.zycfv.cn/Article/details/gt2jpnmndig.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2sbbavkkq.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gt2zcdxytax.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gt2sqjnpckp.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gt2cbtlbged.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gt2tckzdapf.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gt2optfoiky.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvvvsgjk.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gt2lgptnkvb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gt2jcqxwyeb.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gt2eyrlllsm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2jcnzvqan.html

[S36] C++：unordered_map
来源：http://dali.vqdsnc.cn/Article/details/gt2zfwfrxml.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2xidxwdbb.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gt2dgqefjwi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2ttlpdudu.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gt2annlwwpa.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2igzylwfi.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gt2hzutnekk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gt2fwmkskih.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gt2wcxuknyh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anegetwh.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gt2klilqxid.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gt2rmfsbjis.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owqttsue.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gt2eevrewla.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gt2lwsqfdlk.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gt2dsuypvmf.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gt2bvsgusqv.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jnolekbe.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gt2gredxtmy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gt2toncfqiz.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gt2hahbcfvt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gt2wgpveedi.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gt2llhfvzuu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gt2ijabwpbd.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2yubeqkzw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gt2jcynvtkv.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gt2maprljta.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2rokmotna.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gt2jrhcvlwg.html

[S50] C++：格式化数字
来源：http://dali.fengsongda.top/Article/details/gt2wafqugot.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2hsrtmaue.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gt2rftzzcsx.html

static_cast<double>(a) / b
来源：http://dali.zhongyouzk.top/Article/details/gt2qfijwhyc.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gt2mpxvjwgc.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gt2jelfbsau.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gt2rjewztnh.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxldmbim.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gt2rndoxybd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gt2saqgtndj.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhqjsfoj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2ocetwiyt.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gt2egtbawpf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gt2tzhhwxim.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gt2lxkvltlk.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcmvubeu.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gt2drdyfvwp.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gt2rsvphnyw.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gt2oejtcdpw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gt2qfnmlbds.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gt2vxyvopmc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2hezvinsg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2orvflljc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rocxxybw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2oiiqszxv.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2ndbdozqu.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uztmgrlr.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gt2wvkppdru.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gt2foifteor.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gt2fthaspoi.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gt2pgrhylme.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gt2irdqcqdz.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gt2duqcahee.html


<!-- 参考信息 -->