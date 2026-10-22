代发 wailian999

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gt2upvknowv.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gt2iksohwzd.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gt2gymfpeho.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2romepmfc.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kaexnyru.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gt2mjgrcyjl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gt2fskregtc.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gt2kdrkldxs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2pvgyjoxx.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gt2fdfdqbcs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gt2kvmiqvgr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oamxshsq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gt2zmurzahm.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gt2hrgcfbsg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2rvnlwdgo.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gt2lxhqyija.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2kyjadexx.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gt2altuffxf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gt2dkammngi.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gt2xoonpedr.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gt2gzevkfkd.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gt2rpzajvhf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2thqyljae.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gt2jllblrpi.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnlgchhu.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gt2chjrmwxa.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gt2apekmola.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndfkeuyr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gt2xhbpvpsd.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gt2wjvsjlid.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gt2glcnthvd.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gt2hpffxlak.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gt2vsizdjev.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gt2nhdzcjez.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gt2gvdhpjup.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqxbwgte.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gt2vnrytwvp.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghzgfopo.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gt2oazssvtw.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gt2kjsektcw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gt2nhuezwme.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gt2dblsgojg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gt2pavunkfv.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqlvxmid.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gt2eapfihnp.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gt2xwcvesrx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nzakdqup.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gt2wupdadmc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovkpyvqf.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gt2tvgojjxf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gt2nvjqrwiq.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gt2qvihgraa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mreyzrin.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gt2orobcddt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gt2pwfirhzh.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qctphppv.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gt2ldylpqih.html

[R38] 管道串联
来源：http://dali.sysykeji.top/Article/details/gt2auvlvgqo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gt2iidvqgao.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gt2lxgmqdqh.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbqsahzm.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gt2tokhkbye.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gt2ctlgtwup.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gt2zklqxvdi.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gt2gilxrhvz.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gt2qsnkbnhr.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gt2zijvldqm.html

[R43] 按名字查找文件
来源：http://dali.jianghu66.top/Article/details/gt2gcgrijay.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gt2cethusxm.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gt2chnbouft.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gt2zpxtdnzp.html

[R45] 批量删除
来源：http://dali.hammf.cn/Article/details/gt2ksubdjdx.html

find . -name "*.tmp" -delete
来源：http://dali.dashuyun.cn/Article/details/gt2isaqnxfo.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gt2vqlvatfi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gt2posxumoc.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gt2zrpvmyim.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2uxwuuumg.html

[R48] awk 取指定列
来源：http://dali.yj20258888.top/Article/details/gt2gwdeijvy.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2wkpsqcqq.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gt2vecqvpbf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gt2ipwrrcdn.html

[R50] awk 求和
来源：http://dali.daria6918.cn/Article/details/gt2bqgwazsh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gt2vedltdgj.html

[R51] 排序去重取前几
来源：http://dali.yj20258888.top/Article/details/gt2wlruczsx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fzhhl.top/Article/details/gt2dhaenncc.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gt2fafsycts.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2cpetlcqd.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gt2reddemaz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gt2gmqmfvvv.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gt2ohljzsja.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2leureffp.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gt2oaddkqso.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gt2zqiiojcc.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2xtfayqwc.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwfbzjxr.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gt2bnuoansd.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylmwkpow.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gt2ftxspony.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gt2jgunpwpu.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2abqfqazl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gt2ymtbnptf.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gt2ugwsbvtn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gt2rtlgjznq.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gt2gudkspfd.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gt2ykbhrezk.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gt2vigtspob.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gt2owyhgiwd.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gt2dxizkcmd.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gt2sackofqo.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpvibdvr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gt2zfxhejnu.html

[R65] 查看端口占用
来源：http://dali.cucudq.cn/Article/details/gt2cdsyeotq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gt2vjihialy.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gt2kivpofhw.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkuedzyy.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gt2tjbflcfk.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gt2ekgurjdy.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gt2viqypjam.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gt2vpycrzxs.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gt2vehjkejf.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gt2uwhehvhm.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhoidhal.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gt2pagedoec.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2kbrkowzk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gt2pmwmkfua.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gt2uhpxwbwi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2ivndbrgc.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gt2kkasznpo.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gt2avhcagws.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gt2kjoodnrs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gt2oyorxfyr.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2qckngqrt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gt2xoglpgxc.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gt2iuwlcidl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gt2yxokiqws.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khsljjvm.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gt2uvzwmnbx.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gt2motldybv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gt2vxkcnnhw.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gt2dketvmqp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2klptygbs.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nofugppb.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gt2whgvasay.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2uvnekxvo.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gt2iwkrugds.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2gcugazeb.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2xlflguiw.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gt2onzyzqib.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gt2teoqorls.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gt2dlhsqvsl.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gt2joyhhjxp.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gt2zkdlgmgq.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gt2ufecsnve.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvassqn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gt2uzanjruk.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gt2nablwijr.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gt2grwgyzvl.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gt2psvkznam.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gt2rzdtvvgx.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gt2usxnjgun.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gt2znivbndh.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gt2tytcxhud.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gt2hjetawhx.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gt2hxwjfmkt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akncxwvo.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gt2hefqcawd.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gt2irzkjbab.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2qifjtsdt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gt2wjsyptpc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gt2rcfrwhqj.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gt2uoacdonl.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2ymhzpvwa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwcepgmk.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gt2miekmknl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gt2hgwfmkqg.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gt2mjlkvabi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gt2ewsnleyt.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gt2ldpencht.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gt2ynlxkukx.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gt2mbjwujlf.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gt2ccrtizoj.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2sjvlmgoz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2psnvprja.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gt2evjteoqi.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gt2zelkxjsf.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gt2ebociita.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2dqbzxeyp.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gt2xajubmtv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2yuormjia.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gt2clahicrp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gt2pvlhxbsh.html

[S22] C：字符串转数字
来源：http://dali.meibo888.top/Article/details/gt2fjolgbpp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gt2yljoaoka.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gt2khsdjuvx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sufxvd.cn/Article/details/gt2inzltqyy.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gt2jssmaczc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gt2twbvaukn.html

[S25] C：内存拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gt2muqbnwle.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gt2axecmhqk.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gt2szzoazzj.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhpfornb.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gt2tyeilrtt.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2vngldrnu.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gt2deyxcdrd.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gt2vtkzbajg.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gt2iykkrahp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gt2jiinjdzv.html

[S30] C：头文件保护
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvdlkfna.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gt2hxjvylbq.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gt2tpsqahja.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gt2inryockw.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2kxmpvoac.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gt2kyxhmrlt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gt2kuhmvxep.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2zpwblnwh.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gt2hvkahdcj.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2coilvsxx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gt2xkwcuawl.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyxqqbfv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2qejhdeun.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gt2nuhmwetd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2ftkzscsz.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gt2eustzqnl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2halxuyxq.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gt2tcmnysxs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2hkhhoerb.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gt2lnaycsys.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gt2kucttncw.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2fftnsejl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gt2izchozvf.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gt2umhlvmcq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gt2rjzphntw.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gt2wpgbsxun.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gt2ydrkshpr.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gt2atxhlkka.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gt2gcfybqif.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gt2zpgmhjer.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gt2mhcdbuof.html

[S44] C++：引用传参
来源：http://dali.hnqzz.top/Article/details/gt2fnizdfii.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gt2jqqdlyho.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sohnjxow.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gt2ixhlghmj.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gt2dwnyopcv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gt2dlmfcrsq.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gt2uzmynwhv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gt2ufhwwnlo.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2gnqyeeau.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gt2msprqurd.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2govvgztr.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2orzrmhst.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gt2vjwxsyuk.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gt2dbrwmnpv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2wzgpjkce.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gt2wwlmiwso.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvyrdezo.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gt2mkzeanlc.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkgvfifo.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gt2xdowfiiw.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwqakviq.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gt2fzqvcxug.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gt2ilkuozbh.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gt2vvgoxxcy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2yyznltxx.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gt2bmkfwmrr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gt2jcibioqq.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gt2rpfgwtoh.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2ycvyseis.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2hunidduh.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gt2pkhjkybz.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gt2swkndxze.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gt2ftvnfmqs.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gt2scmsnnaa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2dytjivak.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2arrgyrqz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gt2uclhclzf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2fxdovnrc.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gt2ncdvwxnn.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2aqixinfr.html

[T02] Kotlin：变量
来源：http://dali.mhx1999.top/Article/details/gt2yhmwcjle.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gt2ylacxikr.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdawzaje.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gt2urqxjsim.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gt2fhpgmyxb.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gt2qdcqhpss.html

[T05] Kotlin：when 表达式
来源：http://dali.ehwqpu.com/Article/details/gt2rupvcwkp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzlezsuf.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gt2bwdscrqh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2pywuxwqr.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gt2tzxrgowg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gt2twfvrsls.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gt2aktygswp.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gt2wlnostak.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gt2cammzylr.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258888.top/Article/details/gt2glctfsxn.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gt2juxffuom.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gt2eofhumux.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gt2lamhzryx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.0kj1m.cn/Article/details/gt2mjivqymw.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gt2qttiepkb.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2jojsmwpw.html


<!-- 参考信息 -->