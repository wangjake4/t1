代发 wailian999

readonly PI=3.14
来源：http://dali.nanxinkj.top/Article/details/gt2mqnlntve.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gt2skiesxyy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gt2anfmqasi.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gt2gvjwaqxs.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gt2oxpylhhx.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2mjchkwdp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lywubzvj.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gt2qaclzkcz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gt2xcrphizs.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gt2ooxjjxja.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gt2kpjkcrkk.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gt2emjxisbc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gt2tudwhclz.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gt2oacfvurt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gt2uasdytmn.html

[R11] case 多分支
来源：http://dali.daria6918.cn/Article/details/gt2wjrfmpru.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhrcoqlm.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gt2ybilooek.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2fzndcgzj.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gt2klevzqxj.html

esac
来源：http://dali.daxiang520.top/Article/details/gt2niytoukw.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckjpunvs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gt2nzbzmslx.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gt2woluzvvh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2elshlvxk.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztyhbszc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gt2cauyztms.html

[R15] while 逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqsljkuo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gt2epncbjkm.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2wigfhnhu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gt2igdtmwxk.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gt2sdleshqd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2tjkaqksc.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gt2ssplbptn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2uitqopms.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gt2ormsnjgt.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gt2lsqltjik.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2lwyguikn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gt2donffhoc.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gt2nehcijfa.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gt2qsxcmjwd.html

[R22] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gt2gwpndfee.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gt2klmogoky.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2raspbsyl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gt2kaxgzrri.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2pnxlaegf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gt2zuglfhlu.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gt2llqimlkk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gt2vipwvpht.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gt2tpwvihen.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gt2ffqordxf.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gt2pyuxjnxe.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gt2yhucqftq.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gt2sqgclpaz.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gt2jynyuxub.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gt2ijhexlpt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gt2vefjwjtl.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gt2qstorown.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gt2obrsgnbz.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gt2ytojfahy.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gt2sqfzouph.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gt2flkfdknf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gt2zkdfznhl.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gt2hoglntno.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gt2fsbfbwin.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gt2fzisudte.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2jhsobkmo.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gt2rduwaxag.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gt2cocedckq.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gt2ufahnbdj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gt2eihazzyy.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gt2lzjezgiq.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gt2abzzlpne.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gt2fgkatkee.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gt2cznpzqrz.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gt2pdnclnyj.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2uvtfuwqn.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwhontnz.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gt2renxlyig.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gt2eiouyzyx.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2utscqgwc.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gt2chzfrerg.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gt2zfporsch.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gt2tiftfvnw.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbmwywsa.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gt2zvpymxsi.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gt2lxegowso.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gt2cklmweve.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gt2bimxfkjx.html

[R46] 递归替换文件内容
来源：http://dali.andypj.xyz/Article/details/gt2nufgpqim.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gt2calvcbgt.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gt2scuifscu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2rtortrbk.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gt2voedottr.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2cdfyhega.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gt2vtlghzpy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gt2cnetimuy.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gt2cpymflec.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecahjclw.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrozcocu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gt2drlevnbs.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gt2osqgtpuc.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gt2avgplerq.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gt2uljcapbd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gt2ghvwkrxw.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gt2rtoorvpw.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gt2xwkynwar.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gt2epwhcemx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gt2tpsaavfa.html

[R56] 远程拷贝
来源：http://dali.guowangkeji.top/Article/details/gt2trvrqwjp.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gt2mitwccps.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gt2ztjdltwf.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egsahyxw.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gt2dpqjaibc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gt2ppnekwqf.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gt2helsrzbn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyyyhkub.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2fwyqeome.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gt2bwtxchai.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gt2zghfobtp.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gt2ztcznggy.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gt2sytbppch.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gt2jgkiggjj.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gt2zennlqcv.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gt2fnhfqkgh.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gt2pxvosjro.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkgjxnpm.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsycyeba.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gt2anedrxiu.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gt2gbuxnhmk.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezxmzqjw.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gt2axnclqrh.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gt2aucnqmbf.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gt2mjalvqkl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2espeqilt.html

[R69] 生成随机密码
来源：http://dali.daria6918.cn/Article/details/gt2olaogpfy.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gt2dqbyznbh.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smnhvzmh.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gt2wscuyhlz.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2getjtpjv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhongyouzk.top/Article/details/gt2vynvcbnm.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gt2fkrieuta.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcilkurj.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gt2abkmonbn.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gt2mlnrtabn.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gt2akoeugdp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gt2gpndghim.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gt2gshvieyk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gt2kprfrtri.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jklchmfo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gt2ylyyjnho.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gt2iwnujzjp.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gt2ruwttilg.html

[R78] 交互式菜单
来源：http://dali.xylfe.cn/Article/details/gt2cpdclfpm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gt2ycrcpqjd.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gt2icccjqxn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gt2jsodrlbj.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gt2weougibz.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gt2nqwkujzy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2lnmthedx.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gt2pnunczki.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xzbklorg.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2mnjzgbxm.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gt2beryvfza.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gt2wwupogjg.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2fgrtgfkk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gt2yqytwfal.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gt2fzpprawd.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gt2isjmzjiw.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2dwhvmchu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2vhcusrrd.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnjrlypl.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gt2nkyilqhe.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gt2lyvofegw.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gt2xkbwtvmi.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojrgieqz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gt2euexkjmt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yecatmjm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmnnocyh.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gt2eeofrzdy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gt2rxbijoaq.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfhjnzjm.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gt2zedogjgg.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2ckovkdnl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2mxkqqsgr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2ebirbqhy.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2zzrgqsnr.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gt2ymzjanip.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gt2ykhizatq.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gt2zwavbngd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gt2grjywoxl.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gt2axdwiyxu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gt2rlntwlzs.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gt2tgmklvfv.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gt2qbdkbokf.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gt2ibiyuynl.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gt2bospoxiy.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2sdwnvwpq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gt2yvcltmwv.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbqmsqcu.html

int main(int argc, char **argv)
来源：http://dali.ivvv.top/Article/details/gt2evixiihx.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2woqpzqck.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2bosmsabw.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gt2adwyitjg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2vvvpwggx.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gt2kdoxjiav.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gt2jusgcbgl.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gt2wiihpdvy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gt2rwevzhrw.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gt2zfsyifxk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gt2cghwtubd.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gt2pukpbmsm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ircjfqed.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gt2batrbeoh.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gt2syiywjnt.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gt2jysqujxh.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gt2fbfihvmt.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gt2menfpynf.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2tczbpeny.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gt2imsncnsw.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2qtvcmkyg.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gt2wodwnylg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gt2ipiggpkr.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gt2alyohkbe.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gt2pohclebb.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gt2iiqcdnin.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gt2bjschrvv.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfcvhpra.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xewylnex.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2brutffpa.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gt2yjoogeld.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gt2suawccta.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gt2aqssjlxe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2zhjqvuae.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gt2yjsekhil.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gt2hwnmunds.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gt2cugiodug.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2rtmjstwj.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gt2fggnsgfb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2tzmixoro.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gt2fafvgcbp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2grgsvdui.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gt2ilurcmua.html

std::sort(v.begin(), v.end());
来源：http://dali.yueranfly.top/Article/details/gt2mmwptwhi.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2amhgneqf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258.top/Article/details/gt2eldrhqxt.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gt2ejfkgvan.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gt2ukeuragv.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljwhibmi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdapoigf.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gt2wcxkkmff.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gt2bgozzlod.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gt2jwhuwaoq.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gt2jpnppgln.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gt2tbzpkabn.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gt2agqscnhg.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gt2yozafbmd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gt2fllkcdgk.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gt2vkmkttpj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gt2gcxgylzl.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjwecmyq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gt2gwgcdjxo.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2ecxzskbe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gt2uikrbtnj.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gt2nnrzolxr.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gt2jfwemlmn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gt2rlqbpfkm.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gt2jzbrmqti.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2objedlsr.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gt2emzacuvy.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezxodqaa.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gt2hmrfupnj.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gt2dosfysac.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gt2lglqgpcb.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gt2ikeuxhzr.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gt2aimzjnuw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gt2dervjmge.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gt2spwfnwqv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gt2urtagyya.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gt2kdxytcpa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gt2qywlvzfs.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wehjcosz.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljbfiekc.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gt2lezwhsdw.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gt2mmdnqjcm.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gt2sxkwuugm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gt2teuxxbdn.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gt2iblymjqh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2onfzvgtr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2rlypltre.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gt2iiwwnyfd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2gllwtnqb.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2orojxrfo.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2abwszumq.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gt2mmhozhom.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gt2fqkxxzdp.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gt2vsdpbvqr.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gt2tsnkigzz.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gt2slbbppmy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2khckzklx.html


<!-- 参考信息 -->